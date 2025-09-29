# Spaces

Coworking and hotdesking spaces in Scotland, curated by the community for Scottish Technology Club.

## How to contribute

Create a new markdown file in `/content`.

Frontmatter properties:

*Required*:

- `name`
- `city`

*Optional*:

- `web`
- `linkedin`
- `bluesky`

## Development

### Prerequisites

- Node.js 22+ (LTS)
- Git

### Setup

```bash
npm install
```

### Available Commands

```bash
npm run format       # Format all markdown files
npm run format:check # Check if files are formatted
npm run lint         # Lint all markdown files
npm run lint:fix     # Fix linting issues
npm run quality      # Run all quality checks
npm run quality:fix  # Fix all quality issues
```

### Development Tools

- **Prettier** - Code formatting
- **markdownlint-cli2** - Markdown linting
- **Husky** - Git hooks (auto-formatting before commits)
- **GitHub Actions** - CI/CD pipeline

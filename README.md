# Vexara Whitepaper

AI-powered wallet tracking and analytics for Solana blockchain.

## About

This documentation is built with [Mintlify](https://mintlify.com), a modern documentation platform optimized for developer tools and blockchain projects.

## Development

### Prerequisites

- Node.js 18.0 or higher
- npm or yarn

### Installation

Install the Mintlify CLI globally:

```bash
npm install -g mint
```

### Running Locally

Start the development server:

```bash
mint dev
```

The documentation will be available at `http://localhost:3000`

### Project Structure

```
whitepaper/
├── docs.json              # Main configuration file
├── introduction.mdx       # Landing page
├── roadmap.mdx           # Product roadmap
├── developer/            # Developer documentation
│   ├── quickstart.mdx
│   ├── sdk.mdx
│   ├── tools.mdx
│   └── toolkits.mdx
├── use-cases/           # Implementation examples
│   ├── code-generation.mdx
│   ├── data-analysis.mdx
│   └── data-extraction.mdx
├── investor/            # Investment materials
│   ├── overview.mdx
│   ├── value-proposal.mdx
│   └── tokenomics.mdx
├── other/               # Legal and team info
│   ├── team.mdx
│   ├── disclaimer.mdx
│   ├── terms-of-service.mdx
│   └── privacy-policy.mdx
├── assets/              # Images and graphics
└── logo/                # Brand logos
```

## Configuration

### docs.json

The main configuration file contains:
- Site name and branding
- Navigation structure
- Color scheme
- Social links
- Search settings

### Theme Colors

- Primary: #9945FF (Solana purple)
- Light: #14F195 (Solana green)
- Dark: #9945FF

## Adding Content

### Create a New Page

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter with title, description, and icon
3. Write content using Markdown and Mintlify components
4. Update `docs.json` navigation to include the new page

Example:

```mdx
---
title: "Page Title"
description: "Brief description"
icon: "icon-name"
---

## Content Here

Your content...
```

### Available Components

- `<Info>` - Information callout
- `<Warning>` - Warning callout
- `<Check>` - Success callout
- `<Steps>` - Step-by-step guide
- Code blocks with syntax highlighting
- Tables
- Images

## Deployment

### Via Mintlify Dashboard

1. Connect your GitHub repository
2. Mintlify automatically deploys on push to main branch
3. View deployment status in dashboard

### Custom Domain

Configure custom domain in Mintlify dashboard settings.

## Assets

### Images

Place images in `/assets/` directory and reference as:

```markdown
![Alt text](/assets/image.png)
```

### Logos

- `logo/light.png` - Light mode logo
- `logo/dark.png` - Dark mode logo
- `favicon.svg` - Site favicon

## Troubleshooting

### Dev Server Issues

If the dev server isn't running:

```bash
mint update
```

### 404 Errors

Ensure the page is:
1. Listed in `docs.json` navigation
2. File path matches navigation reference
3. Frontmatter is properly formatted

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Mintlify Components](https://mintlify.com/docs/components)
- [Vexara Website](https://vexara.io)
- [GitHub Repository](https://github.com/vexara)

## Support

For questions or issues:
- Email: docs@vexara.io
- Discord: [Vexara Community](https://discord.gg/vexara)
- GitHub Issues: [Report a bug](https://github.com/vexara/docs/issues)

## License

Copyright © 2025 Vexara Inc. All rights reserved.

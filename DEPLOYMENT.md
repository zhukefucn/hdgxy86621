# Deployment Instructions

This project is a Next.js application using Bun as the package manager.

## Prerequisites

- Node.js (recommended version based on package.json)
- Bun installed

## Local Development

1. Install dependencies: `bun install`
2. Run typecheck: `bun typecheck`
3. Run lint: `bun lint`
4. Build the project: `bun build`

## Deployment

For production deployment, you can deploy to platforms like Vercel, Netlify, or your own server.

### Vercel (Recommended for Next.js)

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect Next.js and use the correct build settings
3. Ensure the build command is `bun run build`
4. Deploy

### Manual Deployment

1. Build the project: `bun run build`
2. Start the server: `bun run start`

For more details, refer to Next.js deployment documentation.
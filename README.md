# Replit Node.js 20 Server Project

A TypeScript-based Express server configured for Replit with Node.js 20.

## Project Information

- **Node.js Version**: v22.13.0 (Node.js 20)
- **TypeScript**: Yes (using tsx runtime)
- **Framework**: Express.js
- **Module System**: ESM (ES Modules)
- **Port**: 5000 (mapped to external port 80)

## Files Included

- `.replit` - Replit configuration file
- `package.json` - Node.js dependencies and scripts
- `tsconfig.json` - TypeScript configuration
- `server/index.ts` - Main Express server file

## Available Endpoints

- `GET /` - Main endpoint with server information
- `GET /health` - Health check with uptime and memory usage

## Installation

```bash
npm install
```

## Running the Server

```bash
npm start
# or
npx tsx server/index.ts
```

## Replit Configuration

The `.replit` file is configured with:
- Node.js 20 module
- Nix stable_25_05 channel
- Port mapping: 5000 → 80
- Agent integrations: JavaScript OpenAI AI and Dropbox

## Cloud Storage Locations

This project has been saved to multiple locations:

1. **GitHub**: https://github.com/JonathanShermanEID/replit-nodejs-server
2. **Local Archives**: 
   - `replit-nodejs-project.tar.gz`
   - `replit-nodejs-project.zip`

## Additional Setup for Cloud Storage

To configure rclone for Microsoft OneDrive, Google Drive, or other cloud storage:

```bash
rclone config
```

Follow the interactive prompts to add your cloud storage providers.

## License

MIT

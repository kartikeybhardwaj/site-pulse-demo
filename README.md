# Pulse Demo Site

A live demo application showcasing the capabilities and features of [Pulse](https://github.com/kartikeybhardwaj/pulse).

## About

This is an interactive demonstration of the Pulse project. Explore the features and see Pulse in action.

## Live Demo

Visit the live demo: [demo.pulse.kartikeybhardwaj.com](https://demo.pulse.kartikeybhardwaj.com)

## Getting Started

### Prerequisites

- Node.js and npm installed
- Firebase CLI installed:

  ```bash
  npm install -g firebase-tools
  ```

- Logged into Firebase:

  ```bash
  firebase login
  ```

### Local Development

Install dependencies and start the development server:

```bash
npm install
npm run dev
```

### Testing Locally

Start the Firebase emulator:

```bash
firebase emulators:start --only hosting
```

## Deployment Commands

**Deploy all sites to live:**

```bash
firebase deploy --only hosting
```

**Deploy with a message:**

```bash
firebase deploy -m "Deploy message describing changes"
```

## Previewing Changes (Preview Channels)

**Deploy to a preview channel:**

```bash
firebase hosting:channel:deploy preview-channel-name
```

This creates a temporary URL for testing before deploying to live.

## Checking Deployment Status

**View deployment history:**

```bash
firebase hosting:releases:list
```

**See current configuration:**

```bash
firebase hosting:sites:list
```

## Related Projects

- [Pulse](https://github.com/kartikeybhardwaj/pulse) - The original Pulse project repository

## License

This demo project follows the same license as the original Pulse project.

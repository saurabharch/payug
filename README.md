## Deployment Guide

1. Clone the repository:

   ```bash
   git clone https://github.com/saurabharch/payug.git
   cd payug
   ```

2. Copy environment variables:

   ```bash
   cp .env.example .env
   # Edit .env with your actual config values
   ```

3. Install dependencies:

   ```bash
   npm ci
   ```

4. Run tests:

   ```bash
   npm test
   ```

5. Build and start the service:

   ```bash
   npm run build
   npm start
   ```

---

## Changelog & Releases

- We use [semantic versioning (semver)](https://semver.org/) for all releases.
- Changelog is automatically generated from PR titles following conventional commit messages.
- Releases are published on GitHub with notes.
- Slack notifications are sent to the team channel on every new release.

---
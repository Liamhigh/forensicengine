# forensicengine

Small TypeScript forensic engine helper for Verum-related tooling.

## Quick start

1. Clone the repo:
   git clone https://github.com/Liamhigh/forensicengine.git
   cd forensicengine

2. Install dependencies:
   npm ci

3. Build:
   npm run build

4. Run tests:
   npm test

5. Example usage (Node):
   import { analyze } from './dist/index.js';
   console.log(analyze('some sample data'));

## Development

- Lint:
  npm run lint

- Run in dev:
  npm run start

## Project structure

- src/ - TypeScript source
- dist/ - compiled JavaScript (ignored)
- .github/workflows/ - CI

## Next steps

- Add real analysis logic into src/index.ts
- Add unit tests and sample data
- Tag v0.1.0 when CI passes

# Smart Grid

> Smart Grid is a full-stack project with a visible product surface and supporting service layer.

## The Story

Smart Grid starts with a simple goal: keep the product experience and the service layer visible in one place. Its shape tells the same story: the product interface and the service layer live close enough together that a maintainer can see the project as a whole before diving into individual folders.

## What It Includes

- A user-facing surface for the product, demo, dashboard, or static experience.
- A service layer for APIs, realtime behavior, bot logic, or server-side workflows.

## How It Is Put Together

| Path | Role |
| --- | --- |
| `.eslintrc.json` | project file or folder |
| `.github` | GitHub workflow and repository automation |
| `.gitignore` | ignored local, dependency, and build files |
| `.prettierrc` | project file or folder |
| `LICENSE` | license terms |
| `app` | project file or folder |
| `components` | project file or folder |
| `firebaseConfig.js` | JavaScript source |
| `global.d.ts` | TypeScript source |
| `jsconfig.json` | project file or folder |
| `next-env.d.ts` | TypeScript source |
| `next.config.js` | JavaScript source |

## Local Development

```bash
git clone https://github.com/ENZOMOTIVE/Smart-grid.git
cd Smart-grid
```

```bash
pnpm install
pnpm dev
```

## Command Surface

| Area | Commands |
| --- | --- |
| `package.json` | `dev`, `build`, `start`, `lint` |

## Configuration

- Document API ports, database URLs, third-party credentials, and service endpoints in `.env.example` before deployment.
- Keep wallet private keys, RPC URLs, mnemonics, and contract secrets outside version control.

## Quality Checks

- From the repository root, run `pnpm lint`.
- From the repository root, run `pnpm build`.

## Where To Take It Next

- Add screenshots or a short user flow so visitors can see the interface before running it.
- Document the main API routes, bot events, or service responsibilities with example inputs and outputs.
- Keep setup commands current whenever dependencies, scripts, or deployment targets change.
- Record important product decisions here so the repository keeps its story as the code evolves.

## Project Metadata

| Field | Details |
| --- | --- |
| Repository | `ENZOMOTIVE/Smart-grid` |
| Categories | `Protocol` |
| Primary stack | Next.js, React, Node.js, TypeScript, JavaScript, CSS |


## License

See the repository license file for usage terms.

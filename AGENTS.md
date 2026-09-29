# Project Guidelines

This project is a Job Finder application specifically designed to help @fermeridamagni find a job.

## Rules

- Document and explain why the code is for.
- Get pre-indexed knowledge about the project using the Codegraph MCP.
- Always use up-to-date docs with the Context7 MCP or searching the web. Your knowledge may be outdated.
- Always use Bun as the package manager and runtime environment for TypeScript development.
- Always use UV as the package manager for Python development.
- Always use TypeScript instead of Javascript.
  - Always after writing a `ts` or `tsx` run `bun run check-types` to check for type errors.
- Always use Ultracite (Biome's zero-config preset) for code formatting and linting.
  - Most issues are automatically fixable with `bun run fix`.
  - Before start writing a `ts` or `tsx` file, check the [Ultracite Code Standards](ULTRACITE.md).

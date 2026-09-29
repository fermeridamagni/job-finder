# Project Guidelines

This project is a Job Finder application specifically designed to help @fermeridamagni find a job.

```txt
Soy Fernando Merida Magni, tengo 19 años, 4 años aprendiendo y desarrollando software, y soy de México. Actualmente estoy estudiando la carrera de Ingeniería en Sistemas Computacionales en el Instituto Politecnico Nacion en ESCOM. Me considero una persona responsable, autodidacta y con un gran manejo de software.

La meta es conseguir un trabajo Remoto/Híbrido/Part-Time en México, Latam o USA (sí es híbrido debe de estar ubicado en CDMX o alrededores cercanos) en el que pueda desarrollarme profesionalmente, obtener experiencia, mantenerme y crecer como persona.

Puedes encontrar más información sobre mi en:
- LinkedIn: https://linkedin.com/in/fermeridamagni/
- GitHub: https://github.com/fermeridamagni
- Mi página profesional (La empresa que estoy fundando): https://magni.dev
- Mi CV actual (sin optimizar): ./assets/inital-cv.pdf
```

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

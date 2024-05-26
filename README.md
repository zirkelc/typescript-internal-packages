# TypeScript Feature Request #58657

[Improve support for internal packages by resolving path aliases #58657](https://github.com/microsoft/TypeScript/issues/58657)

Install all dependencies with `pnpm install`.

Then open `apps/foo/src/index.ts` and you will see that TypeScript cannot resolve the dependency to `@repo/libs-with-alias` correctly.
# TypeScript

A hands-on TypeScript project covering core language features from basic types to advanced patterns.

## Learning Objectives

- Basic types in TypeScript
- Interfaces, Classes, and functions
- Working with the DOM and TypeScript
- Generic types
- Namespaces and declaration merging
- Ambient namespaces for external libraries
- Nominal typing with branding

## Project Structure

| Directory | Tasks | Concepts |
|-----------|-------|----------|
| `task_0` | 0 | Interfaces, DOM manipulation |
| `task_1` | 1–4 | Teacher/Directors interfaces, printTeacher, StudentClass |
| `task_2` | 5–7 | Advanced types, type predicates, string literals |
| `task_3` | 8 | Ambient namespaces, `.d.ts` files |
| `task_4` | 9 | Namespaces, declaration merging |
| `task_5` | 10 | Brand convention, nominal typing |

## Requirements

- Ubuntu 18.04
- TypeScript `^4.9.5`
- Webpack `^5`
- Jest `^29`

## Running Each Task

```bash
cd task_X
npm install
npm run build   # Webpack build — must show: No type errors found
npm test        # Jest
```

## Configuration Files (shared across tasks)

- `package.json` — dependencies and scripts
- `.eslintrc.js` — ESLint with `@typescript-eslint`
- `tsconfig.json` — strict TypeScript compiler options
- `webpack.config.js` — Webpack 5 with `ts-loader` and `ForkTsCheckerWebpackPlugin`

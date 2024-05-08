## Overview

Easily kickstart your Node.js projects using TypeScript. Comes pre-configured with ESLint for code linting and GitHub Actions for seamless CI/CD integration via Fly.io. This template enables you to swiftly set up your Node.js applications, ensuring robustness, maintainability, and scalability right from the start.

---

## Features

- TypeScript Support: Write your Node.js code in TypeScript, enabling type safety and improved developer productivity.

- ESLint Integration: Catch potential errors and enforce consistent code style with ESLint, ensuring code quality throughout your project.

- Prettier Support: Maintain consistent code formatting effortlessly with Prettier, enhancing code readability and collaboration within your team.

- esbuild for Bundling: Leverage esbuild to bundle your TypeScript code efficiently, optimizing performance and reducing bundle sizes.

- CI/CD Ready: Utilize GitHub Actions for automated testing, building, and deployment processes, making your development workflow efficient and streamlined.

---

## Getting Started

**System Requirements:**

- **Node**: `version 20.13.0 (LTS)` or higher
- **pnpm**: `version 9.1.0` or higher

### Installation

<h4>From <code>source</code></h4>

> 1. Clone the quick-start-node-ts repository:
>
> ```console
> git clone https://github.com/4D5A90/quick-start-node-ts my-ts-project
> ```
>
> 2. Change to the project directory:
>
> ```console
> cd my-ts-project
> ```
>
> 3. Install the dependencies:
>
> ```console
> pnpm install
> ```

### Usage

<h4>From <code>source</code></h4>

> Run quick-start-node-ts using the command below:
>
> ```console
> pnpm build && pnpm start
> ```
>
> to run the project in development mode:
>
> ```console
> $ > pnpm dev
> ```

### CI/CD

- Get your fly.io [deploy token](https://fly.io/docs/reference/deploy-tokens/)
- Create new [repository secrets](https://docs.github.com/fr/actions/security-guides/using-secrets-in-github-actions) named FLY_TOKEN and paste your fly.io deploy token


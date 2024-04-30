# Master the Developer Experience

## Common Workspace IDE Config

Configure your IDE to work out-of-the-box with the recommended setup!

- [Workspace Extensions](https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions)
- [Workspace Settings](https://code.visualstudio.com/docs/getstarted/settings#_workspace-settings)
- Next step: [Dev Containers](https://code.visualstudio.com/docs/devcontainers/tutorial)

## Command Runner

Use a modern command runner as your daily driver for both local and remote tasks, for an easy and consistent setup.

- [Just](https://github.com/casey/just)
- Just cheatsheet

(Alternatives: Mage, Task)

## Opinionated Formatter

Use an opinionated formatter in your repo, to focus on what's important!

- [CSharpier](https://csharpier.com/) (C#)
- [ruff](https://github.com/astral-sh/ruff) (Python)
- [Prettier](https://prettier.io/) (Everything else)

## Static Documentation Pages

Create an awesome-looking and easy-to-contribute static documentation pages

- [MkDocs](https://squidfunk.github.io/mkdocs-material/)
- [DocFX](https://dotnet.github.io/docfx/)

## Simplify Diagrams

Use [Mermaid.js](https://mermaid.js.org/) to power your diagrams.
- Embedded withing your existing markdown documenation
- Version control

## The Bigger Picture

1. See a recurring issue in PRs
2. Find a tool (or create one) that can detect it (and maybe solve it)
3. Integrate this tool
  a. IDE - Find a plugin
  b. Command Runner - add it to your `just check` (or similiar) command
  c. CI/CD - make sure it runs within your PR Build (should already happen because of step (2)).
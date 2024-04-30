# Master the Developer Experience

Teams often invest in documentation and CI/CD pipelines.
While these are important, make sure you also invest in developer experience!
This will increase productivity within your team and make software development much more fun for everyone.

## Common Workspace IDE Config

Configure your IDE to work out-of-the-box with the recommended setup!

- [Workspace Extensions](https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions)
- [Workspace Settings](https://code.visualstudio.com/docs/getstarted/settings#_workspace-settings)
- Next step: [Dev Containers](https://code.visualstudio.com/docs/devcontainers/tutorial)

## Command Runner

Use a modern command runner as your daily driver for both local and remote tasks, for an easy and consistent setup.

- [Just](https://github.com/casey/just)
- [Just cheatsheet](https://cheatography.com/linux-china/cheat-sheets/justfile/)

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
3. Integrate an IDE plugin
4. Add it to your `just check` (or similiar) command
5. Make sure it runs within your PR Build (should already happen because of step (2)).

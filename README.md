Minimal reproduction
====================

Minimal reproduction of the issue described in [biome-vscode/issues/373](https://github.com/biomejs/biome-vscode/issues/373)

## Steps to reproduce

1. Open the project in VSCode
2. Open the terminal and run `cd application && npm i && npm run check`
3. See the error in the [index.tsx](/application/app-a/WebApp/src/index.tsx) file
4. Now try formatting the file using the `Format Document` command in VS Code and see the error
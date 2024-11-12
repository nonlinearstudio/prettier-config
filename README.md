# Non-Linear Prettier Configuration

## Setup

Make sure to install the [Prettier extension for VSCode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

Make sure to install the dependency as a dev dependency in your project:

```bash
# npm
npm install -D @linear_non/prettier-config
```

Create a .prettierrc file at the root of your project, with just this line inside

```bash
"@linear_non/prettier-config"
```

In VSCode,

1. Cmd + Shift + P
2. Search for "Open User Settings (JSON)"
3. Make sure you have no configuration for formatting other than this line "editor.formatOnSave": true"
4. Reload your VSCode project to make sure changes have applied
5. At the bottom right left, you should have a Prettier button. Errors will show up there. If everything goes well, save a document and it should format accordingly to this configuration.

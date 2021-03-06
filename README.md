# Cadence Visual Studio Code Extension

This extension integrates [Cadence](https://github.com/onflow/cadence), the resource-oriented smart contract programming language of [Flow](https://www.onflow.org/), into [Visual Studio Code](https://code.visualstudio.com/).
It provides features like syntax highlighting, type checking, code completion, etc. 

## Features

- Syntax highlighting (including in Markdown code fences)
- Diagnostics (errors and warnings)
- Code completion, including documentation
- Type information on hover
- Go to declaration
- Go to symbol
- Document outline
- Renaming
- Signature help
- Symbol highlighting
- Code actions
  - Declare constants, variables, functions, fields, and methods
  - Add missing members when implementing an interface
  - Apply removal suggestion
  - Apply replacement suggestion
- Run the emulator, submit transactions, scripts from the editor

## Installation

To install the extension, ensure you [have VS Code installed](https://code.visualstudio.com/docs/setup/mac)
and have configured the [`code` command line interface](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line).

### From the Marketplace

The recommended way to install the latest version of the extension is to get it from the Marketplace.

First, as the extension requires the Flow CLI, [install the CLI](https://github.com/onflow/flow-cli#installation).

Check that the CLI been installed correctly:

```shell script
flow version
```

Finally, [install the extension from the Marketplace](https://marketplace.visualstudio.com/items?itemName=onflow.cadence).

### Using the Flow CLI

The extension can also be installed from the Flow CLI.

First, [install the Flow CLI](https://github.com/onflow/flow-cli#installation).

Check that the CLI been installed correctly:

```shell script
flow version
```

Next, use the CLI to install the VS Code extension:

```shell script
flow cadence install-vscode-extension
```

Restart VS Code and the extension should be installed!

# VSCode Active Claude

A Go CLI tool that modifies VS Code Copilot extension modifications.

## Purpose

This tool helps modify VS Code extensions that start with "github.copilot-chat-" prefix by:
- Finding all VS Code extensions directories starting with "github.copilot-chat-"
- Removing the "...behalf..." string from their extension.js files
- Creating backups of the original files
- Providing the ability to restore from backups


## Installation with Homebrew

You can easily install vs-active-claude using [Homebrew](https://brew.sh):

### Install vs-active-claude

```sh
brew tap az5app/tap
brew install vs-active-claude
```

## License
[Apache 2.0 License](LICENSE)

# hello-world

hey they asked me to change this so i have no choice than to change this, okay.

## How to Add Claude Sonnet to VS Code Copilot Agents

You can use Claude Sonnet as the AI model for GitHub Copilot Chat and agents in VS Code by following these steps:

### Prerequisites

- A paid GitHub Copilot subscription (Pro, Pro+, Business, or Enterprise)
- VS Code with the GitHub Copilot extension installed and up to date

### Steps

1. **Enable Claude Sonnet in GitHub Copilot settings**
   - Go to [https://github.com/settings/copilot/features](https://github.com/settings/copilot/features)
   - Find the Claude Sonnet option and enable it
   - *(For organizations: an admin must enable it in organization Copilot policies)*

2. **Update VS Code and the Copilot extension**
   - Make sure VS Code and the GitHub Copilot extension are updated to their latest versions

3. **Select Claude Sonnet in VS Code**
   - Open the Copilot Chat panel in VS Code
   - Click the model picker (drop-down) at the top of the chat window
   - Select **Claude Sonnet** (e.g., Claude 3.5 Sonnet or Claude 3.7 Sonnet) from the list

4. **Use Claude Sonnet with Copilot agents**
   - Once selected, Claude Sonnet will be used for Copilot Chat, agent mode, and edit mode interactions

### Notes

- Claude Sonnet is available for **Copilot Chat** (ask, edit, and agent modes). Inline code completion may still use a different model.
- If you don't see Claude Sonnet in the model picker, check that your Copilot plan supports it and that it's enabled in your GitHub settings.
- For Business/Enterprise accounts, the organization admin must opt in to allow Claude models before users can select them.

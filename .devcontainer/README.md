# firewalled devcontainer with claude 

function to degit copy the `.devcontainer`, which was copied directly from https://github.com/anthropics/claude-code/tree/main/.devcontainer

```bash
add-claude-dev() {
  npx degit mniederhuber/claude-dev/.devcontainer .devcontainer
}
```
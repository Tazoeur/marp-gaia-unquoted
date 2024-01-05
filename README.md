# List of themes for Marp

A list of tweaked marp themes so it's more to my liking/convenience.

## Prerequisite

- [Marp](https://marp.app/#get-started)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

## Usage

Add the following configuration your `.vscode/setting.json`

```json
{
    // etc...
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/Tazoeur/marp_themes/main/css/rosepine.css",
        // or copy the css file on your disk and use the following
        "./path/to/file.css",
    ],
    // etc...
}
```

then add the desired theme to your markdown file:

```markdown
---
marp: true
theme: rose-pine
class:
    - dawn
    - moon
---
```

## Thanks
Big shoutout to [rainbowflesh](https://github.com/rainbowflesh/) for the rosé pine themes.


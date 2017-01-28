# monokaiC
A monokai theme for the [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing) package for Sublime Text 3 providing both **Coloured** and **text-style preview** for Markdown.

## Install
Clone this repo (`git clone https://github.com/avivace/monokaiC`) and copy `ME-MonokaiC.tmTheme` to the Sublime Text User Package folder (`~/.config/sublime-text-3/Packages/User/` on Linux).

Open your preferred MarkdownEditing User setting file from `Preferences > Package Settings >  Markdown Editing > Markdown (Standard) Settings - USER` (works with MultiMarkdown and Markdown GFM too).

Enable the theme:

```json
{
    "color_scheme": "Packages/User/ME-MonokaiC.tmTheme",
    "extensions":
    [
        "md"
    ]
}
```

## Preview
![example image](screenshot.png)
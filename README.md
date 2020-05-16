# VSCode ERB Toggle

This extensions provides toggle command for ERB tags in VSCode.

Command:
```
erb-toggle.toggleTags
```

## Features

- Cycles through tags `<%= %>`, `<% %>` and `<%= %>`
- Multiline support
- Works in `erb`, `html.erb`, `js.erb`, `css.erb`, `scss.erb`

## Demo

![VSCode ERB Toggle](images/demo.gif?raw=true)

## Keyboard shortcuts

MacOS: `Command+Shift+.`

Windows & Linux: `Ctrl+Shift+.`

To customize keyboard shortcuts:

```
{
  "command": "erb-toggle.toggleTags",
  "key": "ctrl+shift+.",
  "when": "editorTextFocus && editorLangId =~ /erb/"
},
```

## Credits

Inspired by [@vortizhe](https://github.com/vortizhe) plugin [vscode-ruby-erb](https://github.com/vortizhe/vscode-ruby-erb).

## License

This extension is [licensed under the MIT License](LICENSE.txt).

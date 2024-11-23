# dotfiles

My development environment settings

### Terminal PROMPT Config for `.zshrc`

```
setopt PROMPT_SUBST
PROMPT='%n %F{green}●%f ${PWD/#$HOME/~} %F{green}❯%f '
```

Results: `sivadass ● ~/Development/personal/website ❯`

### VSCode Config:

- Theme: [Cobalt2](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)
- Font Name: [OperatorMono-Book](/fonts/OperatorMono-Book.otf)
- Default Editor Config: [.vscode/settings.json](.vscode/settings.json)

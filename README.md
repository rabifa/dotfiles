# Configuração Dotfiles - Windows

Na pasta do usuário crie a pasta **dotfiles**, entre nela e execute:

```
git pull 
```

Volte para a pasta do usuário, abra o **CMD como Administrador** e execute:

```
cd %homepath%

mklink ".gitconfig" "dotfiles\.gitconfig"
```


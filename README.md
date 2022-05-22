# Configuração Dotfiles - Windows

Na pasta do usuário crie a pasta **dotfiles**, entre nela e execute:


Usando SSH
```
git clone git@github.com:rabifa/dotfiles.git 
```

Usando HTTPS
```
git clone https://github.com/rabifa/dotfiles.git
```

---
## Configurando o .gitconfig

Volte para a pasta do usuário, abra o **CMD como Administrador** e execute:

```
cd %homepath%

mklink ".gitconfig" "dotfiles\.gitconfig"
```

---
## Instalando o FiraCode

Entre na pasta **FiraCode** e instale todas as fontes nela contida.
# Configuração Dotfiles - Windows

Entre na pasta do usuário e execute para clonar repositório:


Usando SSH
```
git clone git@github.com:rabifa/dotfiles.git 
```

Usando HTTPS
```
git clone https://github.com/rabifa/dotfiles.git
```

Ou crie a pasta **dotfiles** ente nela e execute os seguintes comendos para manter o verssionamento dos arquivos:

```
git init -b main
```
E depois execute:
Usando SSH
```
git pull git@github.com:rabifa/dotfiles.git 
```

Usando HTTPS
```
git pull https://github.com/rabifa/dotfiles.git
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
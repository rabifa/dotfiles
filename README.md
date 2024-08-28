# Configuração Dotfiles - Windows

>[!IMPORTANT]
>Precisa ter o git instalado!

Entre na pasta do usuário e execute para clonar repositório:

```sh
git clone git@github.com:rabifa/dotfiles.git 
```

## Configurando o .gitconfig

Delete o *.gitconfig* existente.

Volte para a pasta do usuário, abra o **CMD como Administrador** e execute:

```sh
cd %homepath%

mklink ".gitconfig" "dotfiles\.gitconfig"
```

---

## Instalando o FiraCode

Entre na pasta **FiraCode** e instale todas as fontes nela contida.

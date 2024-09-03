# Configuração Dotfiles

>[!IMPORTANT]
>Precisa ter o git instalado!

Entre na pasta do usuário e execute para clonar repositório:

```sh
git clone git@github.com:rabifa/dotfiles.git ~/.dotfiles
```
## Configurando o .gitconfig

De preferência use o terminal do Git para essas ação ou um ambiente Linux.

Caso haja, delete o *.gitconfig* existente.

### Linux

Funciona tanto pelo terminal do Linux quanto pelo terminal do Git.

```sh
cd .dotfiles
ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
```

### Windows 

Volte para a pasta do usuário, abra o **CMD como Administrador** e execute:

```sh
cd %homepath%
mklink ".gitconfig" ".dotfiles\.gitconfig"
```

---

## Instalando o FiraCode

Entre na pasta **FiraCode** e instale todas as fontes nela contida.

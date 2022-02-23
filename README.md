# Instalação e configuração do ZSH

- 1 - Instalar o ZSH com o comando: `sudo apt install zsh`
- 2 -instalar o curl: `sudo apt install curl`
- 3 - executar o script de configuração: `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- 4 -Download repositório: `git clone git@github.com:Ronielli/zshConfig.git ~/.zsh`

## Instalação do tema Dracula:

### Gnome:

- 1 - Executar Comando: `sudo apt-get install dconf-cli`
- 2 - navegar na pasta do repositório: `cd gnome-terminal`
- 3 - executar script de atualização `./install.sh`.

### Outros:

- 1 - Download repositório: `git clone https://github.com/dracula/zsh.git ~/.zsh/dracula-theme`
- 2 - Crie Link Simbólico: `ln -s ~/.zsh/dracula-theme/dracula.zsh-theme ~/.oh-my-zsh/themes/dracula.zsh-theme`
- 3 - Vá para o seu arquivo ~/.zshrc e defina `ZSH_THEME="dracula"`.

## Instalação do plugin Autosuggestions:

- 1 - Download repositório: `git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/autosuggestions`
- 2 - Crie Link Simbólico: `ln -s ~/.zsh/autosuggestions ~/.oh-my-zsh/plugins/zsh-autosuggestions`
- 3 - Vá para o seu arquivo ~/.zshrc e defina:
  ```sh
  plugins=(
      # other plugins...
      zsh-autosuggestions
  )
  ```

## Instalação do plugin Syntax Highlighting:

- 1 - Download repositório: `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.zsh/syntax-highlighting`
- 2 - Crie Link Simbólico: `ln -s ~/.zsh/syntax-highlighting/ ~/.oh-my-zsh/plugins/zsh-syntax-highlighting`
- 3 - Vá para o seu arquivo ~/.zshrc e defina:
  ```sh
  plugins=(
      # other plugins...
     zsh-syntax-highlighting
  )
  ```

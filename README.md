# Ktrinh-s-Vimrc-Setup
This will fetch and install all the plugins you listed:

pangloss/vim-javascript → JavaScript syntax highlighting

mxw/vim-jsx → JSX syntax

leafgarland/typescript-vim → TypeScript syntax

othree/html5.vim → HTML5 support

hail2u/vim-css3-syntax → CSS3 syntax

neoclide/coc.nvim → powerful autocompletion engine

mattn/emmet-vim → Emmet snippets for HTML/CSS

jiangmiao/auto-pairs → auto-close brackets/quotes


HOW TO SET UP 

Vimrc Setup
On Ubuntu/Debian:

sudo apt update
sudo apt install vim git curl nodejs npm -y


👉 On macOS (with Homebrew):

brew install vim git node

2. Plugin Manager

Your config uses vim-plug, so user must install it:

curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

3. Vim Plugins (auto-installed by vim-plug)

Once vim-plug is installed, open Vim and run:

:PlugInstall

4. Extra setup for CoC

After installation, inside Vim run:

:CocInstall coc-tsserver coc-json coc-html coc-css

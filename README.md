# Project Dotfiles

Цей репозиторій містить локальні конфігураційні файли для проекту.

Файли включають:

- `.zshrc` — локальні налаштування shell (aliases, PATH)
- `.gitconfig` — git-конфігурація для цього проекту
- `.vimrc` — налаштування Vim

## Використання на новій машині

1. Встановіть необхідні інструменти:

brew install git chezmoi

 
2. Клонувати репозиторій та застосувати локальні конфігурації:

cd ~/Programming/university
git clone git@github.com:USERNAME/dotfiles.git
cd dotfiles
chezmoi init --apply

3. Активувати локальний .zshrc для проекту:

cd ~/Programming/university/dotfiles
source ./.zshrc
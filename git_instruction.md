# Инструкция по работе с Git

## 1. Установка Git
- **Windows**: Скачайте и установите с [git-scm.com](https://git-scm.com/download/win).
- **MacOS**: Установите через Homebrew (`brew install git`), если у вас его нет, или скачайте с [git-scm.com](https://git-scm.com/download/mac).
- **Linux**: Установите через пакетный менеджер (например, `sudo apt-get install git` для Ubuntu).

## 2. Настройка Git
Откройте терминал и настройте ваше имя и email:
```bash
git config --global user.name "Ваше Имя"
git config --global user.email "ваш.email@example.com"
```

## 6. Подключение удаленного репозитория
```bash
git remote add origin адрес_удаленного_репозитория
git push -u origin master
```


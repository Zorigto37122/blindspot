# Работа с Git

## Первоначальная настройка

Один раз укажи автора коммитов (это не вход в GitHub):

```bash
git config --global user.name "Твоё имя"
git config --global user.email "you@example.com"
```

## Клонирование проекта

Выполнить

```bash
git clone https://github.com/Zorigto37122/blindspot.git
```

подтянуть изменения из удаленного репо

`git pull origin --no-rebase`

загрузить свои изменения

`git push origin main (либо название своей ветки)`

Воркфлоу:

сделали какие то изменения ->
добавили в индекс (выбрать файлы) ->
сделали коммит (`git commit -m "message"`) ->
подтянуть изменения из удаленного репо ->
загрузить свои изменения на удаленный репо


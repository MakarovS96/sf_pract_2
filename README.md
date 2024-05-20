# Simple Project

## Разработка

### Репозиторий
Ссылка:

### Запуск

Сначала нужно склонировать репозиторий локально
```bash
git clone repo
```

Затем устанавливаем и запускаем virtual environment
```bash
python3 -m venv venv
source ./venv/bin/activate
```

Устанавливаем зависимости проекта
```bash
pip3 install -r requirements.txt
```

Запускаем проект локально в тестовом окружении
```bash
flask --app main run
```
Чтобы завершить выполнение жмем <kbd>Ctrl</kbd>+<kbd>C</kbd> в открытом терминале
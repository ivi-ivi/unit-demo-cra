1. Валидация коммитов :heavy_check_mark:
    - без инициализации husky сразу не работает. Необходимо добавить скрипт prepare в package.json (ну или вручную инициализировать)
    https://typicode.github.io/husky/getting-started.html#manual
2. Проверка Pull Request
    - тесты запускают при пул-реквесте :heavy_check_mark:
    - при провале тестов мёрж не запрещён!
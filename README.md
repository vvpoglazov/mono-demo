# mono-demo

Стенд VM Core (фаза 13): монорепозиторий из двух сервисов с заведомо старыми зависимостями —
для проверки компонентов (репозиторий + путь) и сверки CODEOWNERS. Не использовать в работе.

- `services/a` — npm (lodash, minimist)
- `services/b` — pip (Django, PyYAML)
- `package.json` в корне — общий инструмент (handlebars)

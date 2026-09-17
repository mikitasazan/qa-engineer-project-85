# Тестирование в продакшене

[![hexlet-check](https://github.com/mikitasazan/qa-engineer-project-85/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/mikitasazan/qa-engineer-project-85/actions)

Протестируйте проект, который уже работает в продакшене

Учебный проект Хекслета: https://ru.hexlet.io/programs/qa-engineer
Как это должно работать: https://codebattle.hexlet.io/

## Стек

- Тестирование работающего продукта: анализ требований, тест-дизайн, багрепорты, ре-тест
- Артефакты в YAML, проверка структуры — Vitest + jest-json-schema

## Артефакты

- `requirements.yml` — функциональные, нефункциональные и implicit-требования
- `test-cases.yml` — тест-кейсы (по одному требованию на кейс)
- `testing-report.yml` — отчёт о прогоне со статусами
- `issues.yml` — багрепорты по результатам прогона
- `reopened_issues.yml` — ре-тест переоткрытых багов

Объект тестирования: https://codebattle.hexlet.io

## Проверка локально

```bash
git clone https://github.com/mikitasazan/qa-engineer-project-85.git
cd qa-engineer-project-85
```

Файлы читаются любым YAML-парсером, например:

```bash
npx js-yaml requirements.yml
```

---

<details>
<summary>Автоматические тесты Хекслета</summary>

Тесты запускаются на каждый коммит. За запуск отвечает файл `.github/workflows/hexlet-check.yml` — не удаляйте и не переименовывайте ни его, ни репозиторий.

</details>

## О Хекслете

[Хекслет](https://ru.hexlet.io/) — школа программирования: авторские программы обучения с практикой, поддержкой наставников и реальными проектами, которые остаются в резюме. Этот репозиторий — один из таких проектов.

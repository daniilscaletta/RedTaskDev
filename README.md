# CTF Tasks Development

## 📌 Общая концепция
Этот проект создан для разработки, проверки и публикации задач для CTF. Все задачи разрабатываются в отдельных ветках, а после завершения переносятся в основную ветку (`main`). Все подробности в [руководстве](docs/guidelines.md)

---

## 🛠️ Структура репозитория
Основная ветка (`main`) содержит:
- `/category-complexity-task_vuln-task_name/` — только завершённые задачи.
- `/docs/` — документацию проекта.
- `.github/` — шаблоны Issues и Pull Requests.
- `.gitignore` — игнорируемые файлы
- `LICENSE` — лицензия
- `README.md` — общее описание проекта.

Пример структуры:
```plaintext

category-complexity-task_vuln-task_name/  # Завершённые задачи
    deploy/                  # Файлы для раскатки на серваки - Dockerfile, docker-compose.yaml, ...
    give/                    # Файлы для раздачи игрокам
    solution/
        writeup.md           # Райтап
        solution.py          # Сплойт на задание 

docs/                        # Документация
    guidelines.md            # Рекомендации по разработке
    rules.md                 # Правила

.github/ISSUE_TEMPLATE/      # Шаблоны для Issues
    task_template.md         # Шаблон задачи

.gitignore                   # Игнорируемые файлы
LICENSE                      # Лицензия
README.md                    # Руководство

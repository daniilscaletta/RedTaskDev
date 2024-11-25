# CTF Tasks Development

## 📌 Общая концепция
Этот проект создан для разработки, проверки и публикации задач для CTF. Все задачи разрабатываются в отдельных ветках, а после завершения переносятся в основную ветку (`main`).

---

## 🛠️ Структура репозитория
Основная ветка (`main`) содержит:
- `.github/` — шаблоны Issues и Pull Requests.
- `/docs/` — документацию проекта.
- `/redTasks/` — только завершённые задачи.
- `.gitignore` — игнорируемые файлы
- `LICENSE` — лицензия
- `README.md` — общее описание проекта.

Пример структуры:
```plaintext
.github/ISSUE_TEMPLATE/    # Шаблоны для Issues
  task_template.md         # Шаблон задачи

docs/                      # Документация
  guidelines.md            # Рекомендации
  rules.md                 # Правила

redTasks/                  # Завершённые задачи
  task-name1/              
    description.md         # Описание задачи
    solution.py            # Решение задачи
    flag.txt               # Флаг
    writeup.md             # WriteUp задачи

.gitignore                 # Игнорируемые файлы
LICENSE                    # Лицензия
README.md                  # Руководство

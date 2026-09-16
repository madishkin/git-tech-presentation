# Система контроля версий Git и командная разработка

Учебный проект и презентация технологии контроля версий Git. Репозиторий содержит материалы для выступления, конспекты слайдов и наглядную демонстрацию командного Git-flow.

---

## 👥 Команда проекта и зоны ответственности

| Участник | Роль / Тема | Ветка | Папка |
| :--- | :--- | :--- | :--- |
| **@madishkin** (Тимлид) | Архитектура Git, внутреннее устройство (Blob, Tree, Commit, HEAD) | `feature/git-internals` | `parts/part1-basics/` |
| **@участник_2** | Локальный рабочий процесс (`init`, `status`, `add`, `commit`, `diff`, `log`) | `feature/local-workflow` | `parts/part2-branching/` |
| **@участник_3** | Ветвление и слияние (`branch`, `checkout`, `merge`, `rebase`, разрешение конфликтов) | `feature/branches-merge` | `parts/part3-collaboration/` |

---

## 📁 Структура репозитория

```text
git-tech-presentation/
├── README.md                          # Главный документ проекта и регламент
├── .gitignore                         # Игнорируемые файлы
├── presentation.pdf                   # Итоговая презентация для защиты
└── parts/                             # Исходные материалы и слайды по модулям
    ├── part1-basics/
    │   └── content.md                 # Архитектура, снимки состояния, 3 дерева Git
    ├── part2-branching/
    │   └── content.md                 # Базовый локальный пайплайн работы
    ├── part3-collaboration/
    │   └── content.md                 # Ветвление, fast-forward, 3-way merge, rebase
    └── part4-advanced/
        └── content.md                 # Удаленная работа, GitHub flow, Pull Requests
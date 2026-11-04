# AGENTS.md

Telegram-бот: голосовая заметка превращается в связанные заметки в хранилище Obsidian. Это форк `smixs/agent-second-brain`.

- Язык: Python 3.12+, зависимости в `pyproject.toml` и `uv.lock`.
- Код: `src/`, тесты: `tests/`, развёртывание: `deploy/`, `bootstrap.sh`, `setup.sh`, `upgrade.sh`.
- Документация: `README.ru.md`, `docs/`.
- Тесты: `uv run pytest`.
- Настройки берутся из `.env`, образец: `.env.example`. Секреты не коммить.

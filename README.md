# Agent

Песочница для [dsh-superagent](https://github.com/deepseek-ai/dsh-superagent-prototype) —
прототипа проактивного кодинг-агента от DeepSeek.

Агент слушает GitHub-события этого репозитория, оценивает запросы по Policy
и выполняет принятые в отдельной сессии и отдельной git-директории, отвечая
в исходной переписке (обычно pull request'ом).

Запуск сервиса (WSL2):

```sh
wsl -d Ubuntu -u root -e bash -lc "cd /root/src/dsh-superagent && ./scripts/dsh-superagent start"
```

Панель управления: http://127.0.0.1:3082 (URL с токеном печатается в лог при старте).

## Статус

Агент dsh-superagent установлен и работает.

[TOC]

# Aufbau

```bash
$ cat -p .gitignore 
__pycache__/
*.pyc
.env
venv/
env/
instance/
.DS_Store
*.log
```

# Erklärung

| ignore         | Grund                                                                                       |
| :------------- | :------------------------------------------------------------------------------------------ |
| `__pycache__/` | Python's cache ordner die nur die Repo sonst zumüllen.                                      |
| `*.pyc`        | Byte File von Python die nur die Repo sonst zumüllen.                                       |
| `.env`         | beinhaltet Tokens, Passwörter, Credentials, etc.. die nicht remote gepushed werden sollten. |
| `venv/`        | Virtual Envs von Python die nur die Repo sonst zumüllen.                                    |
| `env/`         | beinhaltet Tokens, Passwörter, Credentials, etc.. die nicht remote gepushed werden sollten. |
| `instance/`    | Instanz daten von AWS? zumüllen der Repo.                                                   |
| `.DS_Store`    | MacOs liebt es diesen Ordner immer zu erstellen, ist müll der nicht in die repo gehört.     |
| `*.log`        | Log Files wenn man die App starten im Git Ordner, due müllen nur die Repo zu.               |

# OSiS-docker

## Христофорова, 320

### Практическая Docker

1. Запустить команду docker build -t ghcr.io/hao-pc/osis-docker/node-app:latest . для сбора образа

2. Запустить команду docker run -p 8080:5050 ghcr.io/hao-pc/osis-docker/node-app:latest для запуска контейнера

3. Теперь можно зайти по адресу https://ominous-doodle-9x7ww795x7ghp7gg-8080.app.github.dev

### Практическая Github actions

Для того, чтобы авторизация в GitHub Container Registry в blank.yml (взято в https://github.com/docker/login-action?tab=readme-ov-file#github-container-registry) работала, нужно было выдать права в Settings/Actions/General в разделе Workflow permissions

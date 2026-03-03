## Remnawave Subscription Page

Learn more about Remnawave [here](https://remna.st/).

### Сборка проекта

Проект состоит из фронтенда (Vite + React) и бэкенда (NestJS).

**Фронтенд:**

```bash
cd frontend
npm ci
npm run start:build
```

Или только сборка без проверки типов: `npm run cb` (vite build).

Артефакты попадают в `frontend/dist/`.

**Бэкенд:**

```bash
cd backend
npm ci
npm run build
```

Запуск в production: `npm run start:prod` (из папки backend, после сборки фронтенда — бэкенд раздаёт статику и рендерит страницу подписок).

# Contributors

Check [open issues](https://github.com/remnawave/subscription-page/issues) to help the progress of this project.

<p align="center">
Thanks to the all contributors who have helped improve Remnawave:
</p>
<p align="center">
<a href="https://github.com/remnawave/subscription-page/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=remnawave/subscription-page" />
</a>
</p>

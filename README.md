# Backend Roadmap: Go и PHP

Личный трекер обучения: фундамент, SQL, современный PHP, Go, Docker и CI/CD, архитектура и итоговый проект. ~22 недели, 5 дней в неделю.

Страница: `https://<логин>.github.io/backend-roadmap/`

## Как устроено

- `index.html` — сам трекер, работает на GitHub Pages без сервера.
- `progress.json` — прогресс. Страница читает и обновляет его через GitHub API, поэтому отметки одинаковые на любом устройстве. Каждая отметка — отдельный коммит, так что история обучения видна в `git log`.

## Настройка (один раз)

1. **Включить Pages:** Settings → Pages → Build and deployment → Source: *Deploy from a branch*, Branch: `main`, папка `/ (root)` → Save. Через минуту-две страница появится по адресу выше.
2. **Создать токен:** [github.com/settings/personal-access-tokens/new](https://github.com/settings/personal-access-tokens/new)
   - Token name: `backend-roadmap`
   - Expiration: на свой вкус (например, 1 год)
   - Repository access: *Only select repositories* → `backend-roadmap`
   - Permissions → Repository permissions → **Contents: Read and write**
   - Generate token и скопировать его.
3. **Подключить на устройстве:** открыть страницу, блок синхронизации → вставить токен → «Сохранить». Название репозитория подставится само.

Повторить шаг 3 на каждом устройстве (компьютер, телефон). Токен хранится только в браузере устройства и в репозиторий не попадает.

## Безопасность

- Токен даёт доступ только к этому репозиторию и только к файлам. Если устройство потеряно, просто удалите токен в настройках GitHub и создайте новый.
- Не коммитьте токен в репозиторий.
- Репозиторий публичный (бесплатный GitHub Pages работает только с публичными), поэтому прогресс видят все, у кого есть ссылка.
# backend-roadmap

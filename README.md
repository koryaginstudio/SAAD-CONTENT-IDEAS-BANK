# Банк идей на GitHub Pages + GitHub Issues

Самый простой вариант без Google, сервера и платных сервисов.

## Как работает

- `index.html` публикуется как сайт через GitHub Pages.
- Пользователь заполняет красивую форму.
- После отправки открывается GitHub Issue с уже заполненным текстом.
- Пользователь нажимает `Submit new issue`.
- Идея сохраняется в Issues репозитория.

Важно: пользователю нужен GitHub-аккаунт.

## Шаги запуска

1. Создай новый публичный репозиторий на GitHub, например `SAAD-CONTENT-IDEAS-BANK`.
2. Загрузи в него все файлы из этой папки.
3. Открой `index.html` и замени:

```js
const GITHUB_OWNER = 'koryaginstudio';
const GITHUB_REPO = 'SAAD-CONTENT-IDEAS-BANK';
```

Например:

```js
const GITHUB_OWNER = 'koryaginstudio';
const GITHUB_REPO = 'SAAD-CONTENT-IDEAS-BANK';
```

4. Включи Issues в настройках репозитория:

`Settings → General → Features → Issues`

5. Создай label `idea`:

`Issues → Labels → New label`

6. Включи GitHub Pages:

`Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → root`

7. Получишь ссылку вида:

`https://USERNAME.github.io/REPOSITORY/`

## Как смотреть идеи

Открывай:

`https://github.com/USERNAME/REPOSITORY/issues?q=is%3Aissue+label%3Aidea+sort%3Acreated-desc`

## Ограничения

- Это не настоящая база данных, а хранилище через GitHub Issues.
- Друзьям нужен GitHub-аккаунт.
- Финальный сабмит происходит на стороне GitHub.
- Зато не нужны Google, сервер, Cloudflare, токены и сложная настройка.

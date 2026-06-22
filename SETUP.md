# Как опубликовать профиль на GitHub

Это **отдельный** репозиторий для страницы профиля. Он не связан с другими проектами.

## Шаг 1 — Создать репозиторий на GitHub

1. Откройте https://github.com/new
2. **Repository name:** `gewog` (обязательно совпадает с вашим username!)
3. **Public**
4. Поставьте галочку **Add a README file** (или добавите свой позже)
5. Нажмите **Create repository**

## Шаг 2 — Загрузить README

### Вариант A: через веб-интерфейс

1. Откройте https://github.com/gewog/gewog
2. Нажмите на `README.md` → карандаш (Edit)
3. Вставьте содержимое из `README.md` этого каталога
4. **Commit changes**

### Вариант B: через git

```bash
cd C:\Users\Andy\github-profile-gewog
git init
git add README.md
git commit -m "Add anime-style profile README"
git branch -M main
git remote add origin https://github.com/gewog/gewog.git
git push -u origin main
```

Если репозиторий уже создан с README на GitHub:

```bash
git pull origin main --rebase
git push -u origin main
```

## Шаг 3 — Проверить

Откройте https://github.com/gewog — README должен отображаться на главной странице профиля.

## Опционально: аватар в anime-стиле

1. GitHub → Settings → Profile → **Profile picture**
2. Загрузите anime-аватар (можно сгенерировать на picrew.me или similar)
3. В Bio добавьте: `Python Developer | FastAPI | Async | Microservices`

## Закрепить репозитории

На https://github.com/gewog → **Customize your pins** → выберите 4–6 лучших проектов.

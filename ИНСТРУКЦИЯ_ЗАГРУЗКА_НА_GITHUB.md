# Инструкция: загрузка репозитория на GitHub

## Шаг 1. Создать новый репозиторий на GitHub

1. Войди в аккаунт **krakenssylka2026**
2. Нажми **"+"** → **"New repository"**
3. Заполни:
   - **Repository name:** `kraken-ssylka`
   - **Description:** `Кракен ссылка 2026 — актуальный доступ к Kraken в 2026 году`
   - Выбери **Public**
   - **НЕ** добавляй README, .gitignore, LICENSE (всё уже есть в папке)
4. Нажми **"Create repository"**

---

## Шаг 2. Загрузить файлы

### Вариант A: через веб-интерфейс GitHub

1. На странице нового репо нажми **"uploading an existing file"**
2. Перетащи в окно все файлы из папки `e:\Lesta\github-kraken-ssylka\`:
   - README.md
   - index.html
   - robots.txt
   - sitemap.xml
   - LICENSE
3. Нажми **"Commit changes"**

### Вариант B: через Git (командная строка)

```bash
cd e:\Lesta\github-kraken-ssylka
git init
git add .
git commit -m "Initial commit: Кракен ссылка 2026"
git branch -M main
git remote add origin https://github.com/krakenssylka2026/kraken-ssylka.git
git push -u origin main
```

---

## Шаг 3. Включить GitHub Pages

1. Зайди в **Settings** репозитория
2. В меню слева выбери **Pages**
3. В разделе **Source** выбери **Deploy from a branch**
4. В **Branch** выбери **main** и папку **/ (root)**
5. Нажми **Save**

Через 1–2 минуты сайт будет доступен по адресу:
**https://krakenssylka2026.github.io/kraken-ssylka/**

---

## Шаг 4. Добавить в Яндекс.Вебмастер и GSC

1. **Яндекс.Вебмастер:** добавь сайт `https://krakenssylka2026.github.io/kraken-ssylka/`
2. **Google Search Console:** добавь тот же URL
3. Отправь sitemap: `https://krakenssylka2026.github.io/kraken-ssylka/sitemap.xml`

---

## Результат

- **Страница репо (README):** https://github.com/krakenssylka2026/kraken-ssylka  
- **GitHub Pages (index.html):** https://krakenssylka2026.github.io/kraken-ssylka/  

Оба URL могут индексироваться поисковиками.

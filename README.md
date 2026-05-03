# Vocalibr Brandbook

Single-page brand guidelines for Vocalibr — AI-driven Voice of Customer analytics.

## 🚀 Як задеплоїти на GitHub Pages

### Крок 1 — створити репозиторій
1. Відкрий https://github.com/new
2. Назва: `vocalibr-brandbook` (або будь-яка)
3. Public або Private — без різниці для Pages
4. **Не** додавай README, .gitignore, license — просто Create

### Крок 2 — завантажити файли
1. У новому репо натисни **"uploading an existing file"** (або Add file → Upload files)
2. Перетягни **усі файли з цієї папки** (`index.html` + `README.md`)
3. Commit changes

### Крок 3 — увімкнути Pages
1. Settings → Pages (ліве меню)
2. **Source**: Deploy from a branch
3. **Branch**: `main` / `(root)` → Save
4. Через 30–60 секунд оновлюй сторінку Pages — буде зелена галочка з URL

### Готовий URL
```
https://<твій-username>.github.io/vocalibr-brandbook/
```

---

## 📁 Структура

```
index.html    — головна сторінка брендбуку (single file)
README.md     — цей файл
```

`index.html` self-contained: усе CSS і JS inline, тільки шрифти підвантажуються з Google Fonts (IBM Plex Sans + Mono).

---

## ✏️ Якщо треба редагувати
Файл звичайний HTML — можна відкрити у будь-якому редакторі. Кольори і токени винесені в CSS-змінних на початку `<style>` блоку (`:root { --orange-primary: #ff6b35; ... }`).

---

Made with care · v1.0

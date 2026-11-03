# Verb Rush

Інтерактивна гра для студентів рівня A2–B1: тренуємо **verb patterns** (які форми йдуть після дієслів).
Дієслова падають зверху, а ти відправляєш їх у правильні кольорові ворота:

| Ворота | Правило | Приклад |
|---|---|---|
| to → | verb + to + infinitive | I want **to be** a YouTuber |
| -ing ⟳ | verb + -ing | I enjoy **playing** games |
| + me to | verb + person + to | Mum told **me to** clean |
| NO TO | make / let + person + verb | Dad let **me stay** up |

Керування: тап по воротах або клавіші `1 2 3 4` / `A S D F`.
Є рівні, комбо-множник, 3 життя, рекорд і розбір помилок.

## Як запустити
Це один файл `index.html`, без залежностей. Просто відкрий його в браузері.

## Як опублікувати на GitHub Pages
1. Створи репозиторій на github.com (наприклад `verb-rush`).
2. Завантаж файли `index.html` і `README.md` (Add file → Upload files).
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, папка `/ (root)` → Save.
4. Через 1–2 хвилини гра буде тут: `https://<твій-нік>.github.io/verb-rush/`

Через термінал:
```bash
git init
git add index.html README.md
git commit -m "Verb Rush"
git branch -M main
git remote add origin https://github.com/<твій-нік>/verb-rush.git
git push -u origin main
```

## English
A small browser game that trains English verb patterns (to + infinitive, -ing, verb + object + to, make/let + bare infinitive). Single file, no dependencies. Enable GitHub Pages to host it.

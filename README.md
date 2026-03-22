# Manacost Dev — Официальный сайт-визитка

> Сайт команды **Manacost Dev** — крупнейшего русскоязычного сообщества по Hearthstone.

🌐 **[manacostdev.vercel.app](https://manacostdev.vercel.app)**

---

## О проекте

Одностраничный сайт-визитка в стиле игры Hearthstone. Рассказывает о команде, проектах, вакансиях, услугах и партнёрах.

**Стек:** Vanilla HTML · CSS · JavaScript (без фреймворков)
**Деплой:** Vercel
**Аналитика:** Vercel Analytics

---

## Структура файлов

```
manacostdev.ru/
├── index.html                  # Единственная страница
├── favicon.ico                 # Иконка сайта
├── README.md
│
└── assets/
    ├── fonts/
    │   └── 2318-font.otf       # Кастомный шрифт Hearthstone
    │
    └── images/
        ├── logo/
        │   ├── manacost-logo.png       # Лого команды
        │   └── hearthstone-logo.png    # Лого Hearthstone
        │
        ├── social/
        │   ├── telegram.png    # Иконка Telegram
        │   ├── vk.svg          # Иконка ВКонтакте
        │   └── boosty.png      # Иконка Boosty
        │
        ├── icons/
        │   └── read.png        # Иконка кнопки «Открыть»
        │
        ├── projects/
        │   ├── hs-manacost.png         # Обложка hs-manacost.ru
        │   ├── kolodahearthstone.png   # Обложка kolodahearthstone.ru
        │   ├── hs-arena.png            # Обложка hs-arena.ru
        │   └── koloda-bot.jpg          # Обложка @manacostcard_bot
        │
        ├── vacancies/
        │   ├── arena.webp              # Иконка режима Арена
        │   ├── battleground.webp       # Иконка Поля Сражений
        │   ├── standart.webp           # Иконка Стандарт
        │   └── wild.webp               # Иконка Вольный
        │
        └── partners/
            ├── blizzard.png
            ├── cybersport.png
            ├── honor.png
            ├── mail.webp
            ├── playerok.png
            ├── samsung.png
            └── msk-esports.svg
```

---

## Секции сайта

| Секция | Описание |
|--------|----------|
| **Hero** | Логотип, заголовок, описание команды, статистика (108к ВК / 7.5к TG / 500к посещений) |
| **Наши проекты** | Карточки 4 проектов с обложками |
| **Мы работали с** | Логотипы партнёров (Blizzard, Samsung, Honor и др.) |
| **Вакансии** | 4 позиции авторов (Арена, Поля Сражений, Стандарт, Вольный) с раскрывающимися требованиями |
| **Услуги** | Разработка сайтов/ботов + рекламный медиакит |
| **Контакты** | Email, Telegram, VK, Boosty, техподдержка, реклама |

---

## Наши проекты

| Проект | Описание | Ссылка |
|--------|----------|--------|
| **hs-manacost.ru** | Крупнейшее СМИ по Hearthstone на русском | [hs-manacost.ru](https://hs-manacost.ru) |
| **kolodahearthstone.ru** | Клуб по подписке с авторскими гайдами | [kolodahearthstone.ru](https://kolodahearthstone.ru) |
| **hs-arena.ru** | Статистика и помощник для режима Арена | [hs-arena.ru](https://hs-arena.ru) |
| **@manacostcard_bot** | Telegram-бот генерации картинки колоды | [t.me/manacostcard_bot](https://t.me/manacostcard_bot) |

---

## Социальные сети

| Платформа | Ссылка | Аудитория |
|-----------|--------|-----------|
| ВКонтакте | [vk.com/manacost](https://vk.com/manacost) | 108 000 подписчиков |
| Telegram | [t.me/manacost_ru](https://t.me/manacost_ru) | 7 500 подписчиков |
| Boosty | [boosty.to/kolodahearthstone](https://boosty.to/kolodahearthstone) | — |

---

## Контакты

| Назначение | Контакт |
|------------|---------|
| Общие вопросы | [admin@hs-manacost.ru](mailto:admin@hs-manacost.ru) |
| Техподдержка | [@manacostHS](https://t.me/manacostHS) |
| Реклама и сотрудничество | [@LordZulut](https://t.me/LordZulut) |

---

## Локальный запуск

```bash
# Достаточно открыть index.html в браузере
# Или поднять локальный сервер:
npx serve .
# либо
python -m http.server 8080
```

---

*Hearthstone® является товарным знаком Blizzard Entertainment, Inc. Сайт не связан с Blizzard Entertainment.*

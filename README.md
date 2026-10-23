markdown
# Форма 043/у · Портал

> Медицинская карта стоматологического больного (веб-версия). Деплой-репозиторий портфолио. **Не медизделие.**

[**Открыть портал →**](https://stomvrn.github.io/)

---

## Что это

Это репозиторий, из которого **деплоится** портфолио. Один файл — `index.html` — оформлен как форма № 043/у (медицинская карта стоматологического больного, утв. приказом Минздрава СССР от 04.10.1980 № 1030).

Портал — справочно-образовательный артефакт. Не предназначен для диагностики, лечения или клинических решений. Не заменяет врача и обучение первой помощи.

## Три слоя

Идентичность и discovery живут в основном репозитории профиля. Этот репозиторий — доказательство (proof).

| Слой | Файл | Где |
|---|---|---|
| Identity | README (медкарта), `devcard.json` | [stomvrn/stomvrn](https://github.com/stomvrn/stomvrn) |
| Discovery | `llms.txt`, `artifact.json` | [stomvrn/stomvrn](https://github.com/stomvrn/stomvrn) · [корень сайта](./llms.txt) |
| Proof | `index.html` (форма 043/у), 5 артефактов | **этот репозиторий** |

## Структура
stomvrn.github.io/
├── index.html ← форма 043/у, деплой на https://stomvrn.github.io/
├── llms.txt ← индекс для AI-краулеров (корень домена)
├── robots.txt ← разрешение для AI-ботов
└── README.md

text

## Публичные артефакты

Портал ссылается на 5 артефактов. Все — single-file HTML, офлайн, с открытой лицензией, с URN.

| # | Артефакт | Что | Лицензия |
|---|---|---|---|
| 01 | [Emergency Help](https://stomvrn.github.io/emergency-help/) | 16 карточек (14 алгоритмов + 2 справки) | CC0 |
| 02 | [LLM Cheatsheet](https://stomvrn.github.io/stomvrn-llm-cheatsheet/) | 24 плитки, 5 разделов | CC BY 4.0 |
| 03 | [Medical Kit](https://stomvrn.github.io/medical-kit/) | 9 клинических шкал, 102 навыка | CC BY 4.0 |
| 04 | [Clinical Communication](https://stomvrn.github.io/clinical-communication-assistant/) | 15 этапов, 102 навыка | CC BY 4.0 |
| 05 | [vanxo-tools](https://stomvrn.github.io/vanxo-tools/) | 14 утилит | CC0 |

## Принципы

- **Offline-first** — работает без интернета.
- **Single-file** — один HTML, без сборки.
- **Zero dependencies** — нет CDN, шрифтов, библиотек, аналитики.
- **Strict CSP** — `connect-src 'none'`.
- **Local-only** — данные не покидают устройство.
- **Открытая лицензия** — CC0 или CC BY 4.0.
- **URN-идентификация** — `urn:vanxo:artifact:portfolio:2.0.0`.

## Деплой

- Источник: ветка `main`, корень `/`.
- URL: [stomvrn.github.io](https://stomvrn.github.io/).
- Обновление: пуш в `main` → GitHub Pages пересобирает в течение 1–2 минут.

## Дисклеймер

**Not a medical device.** For educational and reference use only. Not intended for diagnosis, treatment, or clinical decision-making.

**152-ФЗ.** Do not enter personally identifiable patient information.

## Контакты

- GitHub: [@stomvrn](https://github.com/stomvrn)
- Telegram: [@ivan_kholin_digital](https://t.me/ivan_kholin_digital)
- Email: stom.vrn@gmail.com
- ORCID: [0009-0005-7588-989X](https://orcid.org/0009-0005-7588-989X)

## Лицензия

CC BY 4.0 · `urn:vanxo:artifact:portfolio:2.0.0`

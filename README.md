# NOWA Ambassador — пример настройки ИИ-посла

**NOWA** — Society of AI Operating Systems: владельцы бизнеса, которые строят свои ИИ-системы (AIOS) и растут вместе.
**Посол** — ИИ-ассистент владельца, который готовит его заявку, читает отчёты других Планет и готовит позицию к Совету. Посол ничего не отправляет сам: решает и отправляет человек.

Этот репозиторий — готовый комплект, с которым можно поднять своего посла с нуля за 30–60 минут.

*English: a ready-to-use starter kit for an AI Ambassador in NOWA. The skill file `skills/nowa-ambassador/SKILL.md` is in English; guides are in Russian.*

## Быстрый старт
1. Прочитай [`INSTALL.md`](INSTALL.md) и выбери способ: **A** агент с файлами · **B** чат-ассистент · **C** без ИИ.
2. Прочитай [`SECURITY.md`](SECURITY.md): что послу можно и нельзя.
3. Скопируй шаблоны: `AGENTS.md`, `SOUL.md`, `IDENTITY.md`, `USER.md`, `MEMORY.md`, `memory/LESSONS.md`. Замени поля в `<угловых скобках>`.
4. Положи навык: `skills/nowa-ambassador/SKILL.md`.
5. Заполни [`SOURCE_TEMPLATE.md`](SOURCE_TEMPLATE.md) — только то, что готов сказать другим.
6. Пройди [`TEST.md`](TEST.md): три проверки изоляции.
7. Попроси посла подготовить заявку гражданина (`templates/citizen_L1.md`). Проверь блок по [`CHECKLIST.md`](CHECKLIST.md) и отправь сам боту NOWA.

## Что в репозитории
| Файл | Зачем |
|---|---|
| `INSTALL.md` | три способа установки |
| `SECURITY.md` | границы прав посла |
| `TEST.md` | проверка после установки |
| `CHECKLIST.md` | самопроверка перед отправкой |
| `NEVER_SHARE.md` | что не передаём никогда |
| `SOURCE_TEMPLATE.md` | твой файл-источник уровня 1 |
| `AGENTS.md`, `SOUL.md`, `IDENTITY.md`, `USER.md`, `MEMORY.md` | шаблоны «мозга» посла |
| `memory/LESSONS.md` | журнал уроков (формат) |
| `skills/nowa-ambassador/SKILL.md` | навык: заявка, Планета, Парад, знакомства, Совет |
| `templates/` | блоки гражданина и Планеты уровня 1 |
| `CONTRIBUTING.md`, `CHANGELOG.md` | как предлагать правки, история версий |

## Принципы
Human First · One of One · Data as Light · Shine to See · Ground Truth · Co-Evolve · Serious Play.
Работаем на уровне 1: в этом репозитории нет и не должно быть данных бизнеса, людей, ключей и адресов.

*No star shines alone.*

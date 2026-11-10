# Полный каталог мест для хуков

Сгенерировано `hook_scan.py --catalog`. Каждый метод можно перехватить: `api.hook_by_name(класс, имя, before, after, replace)`.
Для вложенных классов имя через `$` (так его понимает Java). Приватные методы не включены. Классификация эвристическая.

Машинный вид: [hooks.json](hooks.json) (поля: class, method, params, returns, kind, category, static).

| Вид | Категория | Методов | Файл |
|---|---|---|---|
| function | call | 664 | [function_call.md](function_call.md) |
| function | chat | 782 | [function_chat.md](function_chat.md) |
| function | dialogs | 29 | [function_dialogs.md](function_dialogs.md) |
| function | emoji | 167 | [function_emoji.md](function_emoji.md) |
| function | login | 72 | [function_login.md](function_login.md) |
| function | media | 1737 | [function_media.md](function_media.md) |
| function | network | 6466 | [function_network.md](function_network.md) |
| function | notifications | 164 | [function_notifications.md](function_notifications.md) |
| function | other | 5773 | [function_other.md](function_other.md) |
| function | profile | 104 | [function_profile.md](function_profile.md) |
| function | settings | 339 | [function_settings.md](function_settings.md) |
| function | stories | 287 | [function_stories.md](function_stories.md) |
| function | theme | 568 | [function_theme.md](function_theme.md) |
| visual | call | 894 | [visual_call.md](visual_call.md) |
| visual | chat | 2225 | [visual_chat.md](visual_chat.md) |
| visual | dialogs | 406 | [visual_dialogs.md](visual_dialogs.md) |
| visual | emoji | 1458 | [visual_emoji.md](visual_emoji.md) |
| visual | login | 263 | [visual_login.md](visual_login.md) |
| visual | media | 2810 | [visual_media.md](visual_media.md) |
| visual | network | 100 | [visual_network.md](visual_network.md) |
| visual | notifications | 67 | [visual_notifications.md](visual_notifications.md) |
| visual | other | 15727 | [visual_other.md](visual_other.md) |
| visual | profile | 663 | [visual_profile.md](visual_profile.md) |
| visual | settings | 391 | [visual_settings.md](visual_settings.md) |
| visual | stories | 2038 | [visual_stories.md](visual_stories.md) |
| visual | theme | 3202 | [visual_theme.md](visual_theme.md) |

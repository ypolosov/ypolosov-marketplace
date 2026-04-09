# ypolosov-marketplace

Персональный маркетплейс плагинов [Claude Code](https://code.claude.com/docs) от [ypolosov](https://github.com/ypolosov).

## Установка маркетплейса

В Claude Code добавьте каталог (репозиторий на GitHub, ветка по умолчанию — `main`):

```text
/plugin marketplace add ypolosov/ypolosov-marketplace
```

Из CLI (см. [Create and distribute a plugin marketplace](https://code.claude.com/docs/en/plugin-marketplaces)):

```bash
claude plugin marketplace add ypolosov/ypolosov-marketplace
```

Обновить локальную копию каталога: `/plugin marketplace update` (или аналог в CLI).

## Плагины в каталоге

| Плагин | Репозиторий |
|--------|----------------|
| **ai-driven-sdlc** | [ypolosov/ai-driven-sdlc-plugin](https://github.com/ypolosov/ai-driven-sdlc-plugin) |
| **fpf-ai** | [ypolosov/fpf-ai](https://github.com/ypolosov/fpf-ai) |
| **add-ai** | [ypolosov/add-ai](https://github.com/ypolosov/add-ai) |

## Установка плагина ai-driven-sdlc

После подключения маркетплейса (идентификатор каталога — поле `name` в `marketplace.json`, здесь `ypolosov-marketplace`):

```text
/plugin install ai-driven-sdlc@ypolosov-marketplace
```

```bash
claude plugin install ai-driven-sdlc@ypolosov-marketplace
```

## Лицензия

Записи в каталоге ссылаются на лицензии соответствующих репозиториев плагинов.

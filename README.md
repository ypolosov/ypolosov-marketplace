# ypolosov-marketplace

Персональный маркетплейс плагинов [Claude Code](https://code.claude.com/docs) от [ypolosov](https://github.com/ypolosov).

## Установка маркетплейса

В Claude Code добавьте маркетплейс по URL репозитория (ветка `main`), затем установите нужный плагин.

```text
/plugin marketplace add ypolosov/ypolosov-marketplace
```

Если команда отличается в вашей версии клиента, используйте документацию: [Claude Code plugins](https://code.claude.com/docs).

## Плагины в каталоге

| Плагин | Репозиторий |
|--------|----------------|
| **ai-driven-sdlc** | [ypolosov/ai-driven-sdlc-plugin](https://github.com/ypolosov/ai-driven-sdlc-plugin) |
| **fpf-ai** | [ypolosov/fpf-ai](https://github.com/ypolosov/fpf-ai) |
| **add-ai** | [ypolosov/add-ai](https://github.com/ypolosov/add-ai) |

## Установка плагина ai-driven-sdlc

После подключения маркетплейса:

```text
/plugin install ai-driven-sdlc@ypolosov-marketplace
```

Точное имя маркетплейса в UI может совпадать с полем `name` в `.claude-plugin/marketplace.json` (`ypolosov-marketplace`).

## Лицензия

Записи в каталоге ссылаются на лицензии соответствующих репозиториев плагинов.

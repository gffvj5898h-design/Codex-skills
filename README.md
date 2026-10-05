# Codex Skills

Личная коллекция из 63 установленных Agent Skills для Codex.

## Установка в десктопный Codex

В терминале компьютера, на котором установлен Codex, выполните:

```bash
npx skills add gffvj5898h-design/Codex-skills -a codex -g
```

Выберите нужные навыки в установщике. Для установки всех навыков без выбора:

```bash
npx skills add gffvj5898h-design/Codex-skills -a codex -g --all -y
```

Флаг `-g` устанавливает навыки для пользователя компьютера, а не для одного проекта. После установки перезапустите Codex или начните новую сессию.

Репозиторий публичный; для скачивания авторизация GitHub не требуется.

Альтернатива: скачайте репозиторий и скопируйте папки из `skills/` в `~/.agents/skills/`.

## Источники

| Источник | Skills |
| --- | ---: |
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 50 |
| [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) | 1 коллекция |
| [remotion-dev/skills](https://github.com/remotion-dev/skills) | 12 |

Это снимок установленных навыков. Оригинальные авторы сохраняют права на материалы; найденные лицензии источников находятся в `upstream-licenses/` и внутри навыков. Для Remotion отдельный файл лицензии в исходном репозитории не найден; условия использования уточняйте у источника. `skills-lock.json` сохраняет сведения об исходных установках.

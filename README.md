# Kinetica Docs

Руководство по редактору роботов [Kinetica Editor](https://github.com/Kinetica-Labs/kinetica-editor) — в картинках, на русском и английском.

**Читать: https://kinetica-labs.github.io/kinetica-docs/**

A picture guide to the [Kinetica Editor](https://github.com/Kinetica-Labs/kinetica-editor), a robotics editor — in Russian and English.

**Read: https://kinetica-labs.github.io/kinetica-docs/**

## Что здесь

| Файл | Что это |
|---|---|
| `index.html` | страница сайта: урок по шагам, главы, переключатель языка |
| `interface.md`, `interface.en.md` | текст руководства — его же читает страница |
| `images/ui/` | снимки окна редактора, значки кнопок и клип результата |

## Как это обновляется

Картинки не рисуют руками: редактор без показа окна выполняет каждую функцию и фотографирует себя. Скрипты живут в
репозитории редактора:

```sh
python3 tools/ui_guide_shots.py                # переснять картинки
python3 tools/ui_guide_icons.py --write        # расставить значки кнопок в тексте
python3 tools/build_site.py ../kinetica-docs   # собрать сайт в эту папку
```

Нашли ошибку или непонятное место — откройте issue в этом репозитории.

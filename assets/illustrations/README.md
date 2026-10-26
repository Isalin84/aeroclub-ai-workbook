# Иллюстрации блоков

Слоты: b0-start, slovar, b1-map, b2-safety, b3-prompts, b4-skills, b5-docs, b6-dashboard, b7-visual, b8-present, b9-vibe, b10-final, boarding - файлы `<слот>.webp`. Тетрадь работает и без них.

Картинки генерируются в ChatGPT (GPT Image 2.5) в одном стиле: бумажная аппликация в палитре Аэроклуба (графит, красный акцент, белый, светло-серый, сталь, бледно-голубой), тема - авиация и мероприятия. Промпты - в `../../../_tools/illustration_prompts.md`, исходники 1536×1024 - в `../../../_tools/illustrations_src/`, обрезка до 3:1 (баннеры, 1536×512) и 570:395 (`boarding`, арт для посадочного талона-сертификата) - `../../../_tools/crop_illustrations.py`. Перегенерировали картинку - положили PNG в исходники под тем же именем и запустили скрипт: `_tools/.venv/bin/python _tools/crop_illustrations.py`.

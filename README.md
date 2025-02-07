# VILLKA
VILLKA is an anagram of the first letters of the [AI Learning Lab](https://ai-learninglab.itmo.ru/) competition and track names (VK).

# Setup
1. Настройка папок с данными

Нужно создать папки для хранения данных (./data/input, ./data/output) и записать абсолютные пути к ним в файл .env:
- INPUT_DATA_PATH - для входных данных,
- OUTPUT_DATA_PATH - для выходных данных.

2. Создание среды окружения

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Установка пакетов

```bash
pip install -r requirements.txt
# Install torch for your device
pip3 install torch torchvision
```

# Prerequisites
- Python version: 3.9.2

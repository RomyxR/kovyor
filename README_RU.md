# Kovyor

Инструмент на основе RVC и Demucs, который помогает автоматически создавать AI-каверы. Нужна только модель RVC и ссылка на видео YouTube.

## Возможности

- **Автоматическое создание AI-каверов**: Создавайте каверы с минимальными усилиями
- **Интеграция с RVC**: Используется Retrieval-based Voice Conversion для высококачественного синтеза голоса
- **Интеграция с Demucs**: Продвинутое разделение аудио для чистого извлечения вокала
- **Поддержка YouTube**: Прямая обработка по ссылке на видео с YouTube
- **Простой процесс**: Просто укажите модель и ссылку на видео

## Требования

- [Python 3.10.x](https://www.python.org/downloads/release/python-3110/)
- [FFmpeg](https://ffmpeg.org/download.html)

## Быстрый старт

### Windows
Запустите следующий batch-файл для создания виртуального окружения и установки зависимостей:
```bash
create_venv_and_download_requirements.bat
```

Затем запустите приложение с помощью:
```bash
kovyor.bat
```

### Linux
Запустите следующий shell-скрипт для настройки окружения:
```bash
./create_venv_and_download_requirements.sh
```

Затем запустите приложение командой:
```bash
./kovyor.sh
```

> [!TIP]
> Кстати, вы можете не указывать Index файл, если его нет, но качество может быть ниже.

## Благодарности

- [RVC](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion) - Retrieval-based Voice Conversion
- [Demucs](https://github.com/facebookresearch/demucs) - Разделение музыкальных источников

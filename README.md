# Kovyor
[Russian](README_RU.md)

An RVC and Demucs-based tool that helps create AI covers automatically. Only an RVC model and a YouTube video link are needed.

## Features

- **Automatic AI Cover Generation**: Create AI-generated covers with minimal effort
- **RVC Integration**: Utilizes Retrieval-based Voice Conversion for high-quality voice synthesis
- **Demucs Integration**: Advanced audio separation for clean vocal extraction
- **YouTube Support**: Direct processing from YouTube video links
- **Simple Workflow**: Just provide a model and video link

## Requirements

- Python 3.10.x
- FFmpeg

## Quick Start

### Windows
Run the following batch file to create a virtual environment and install dependencies:
```bash
create_venv_and_download_requirements.bat
```

Then, launch the application using:
```bash
kovyor.bat
```

### Linux
Run the following shell script to set up the environment:
```bash
./create_venv_and_download_requirements.sh
```

Then, start the application with:
```bash
./kovyor.sh
```
### Аdvice
By the way, you can omit the Index file if it doesn't exist, but the quality may be lower.


## Acknowledgments

- [RVC](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion) - Retrieval-based Voice Conversion
- [Demucs](https://github.com/facebookresearch/demucs) - Music source separation

# GlobeSynth

GlobeSynth is an innovative platform that utilizes advanced natural language processing and deep learning techniques to transform press releases into engaging multimedia content. The project leverages Wav2Lip, Key-BERT models, GTTS, moviepy, and icrawler libraries to achieve its objectives.

## Project Overview

The aim of GlobeSynth is to convert text-based press releases into visually appealing videos. The input to the system consists of different press releases from various sources across the country. The platform then processes this input, extracts key points from the text, translates it into any of the 14 supported languages, and generates compelling videos with synchronized audio translations.

## Features

- **Text to Video Conversion**: Convert text-based press releases into multimedia videos.
- **Multilingual Support**: Translate press releases into 14 supported languages.
- **Key Point Extraction**: Identify and extract key points from the input text for video content generation.
- **Deep Fake Models**: Utilize Wav2Lip for deep fake audio-to-video synthesis.
- **API Integration**: Integrate with various APIs for audio translations and text processing.
- **Open Source**: The project is open-source, allowing for contributions and customization.

## Getting Started

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/globe-synth.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

### Usage

1. Place your press release text files in the `data/` directory.
2. Run the main script to generate videos:
   ```
   python src/main.py
   ```

### Configuration

- Configure API keys and other settings in `config.py`.
- Adjust video generation parameters in `src/video_generation.py`.

# Music-Generation-LSTM
Welcome to the AI Music Generation using LSTM GitHub repository! This project focuses on creating a powerful and creative artificial intelligence model that generates music using Long Short-Term Memory (LSTM) networks.

## Overview:
AI-generated music has gained immense popularity due to its ability to produce unique compositions, assist musicians, and inspire new melodies. This repository provides a comprehensive implementation of a music generation system using LSTM, a type of recurrent neural network (RNN) known for its proficiency in modeling sequences, making it an ideal candidate for generating music.

## Key Features:

LSTM Architecture: The core of this project lies in the LSTM neural network architecture. LSTMs are chosen for their capability to capture long-range dependencies and patterns within sequential data, which aligns perfectly with the structure of musical compositions.

MIDI Integration: The repository includes functionalities to process MIDI files, which are commonly used for representing musical data. MIDI files are parsed, preprocessed, and used as input for the LSTM model.

Music Generation: Once the model is trained, you can generate new music by providing an initial seed sequence. The LSTM network will then predict subsequent notes based on the learned patterns, resulting in the creation of original and coherent musical pieces.

## Installation

To run this project locally, follow these steps:

1. **Clone** the repository:

    ```bash
    git clone https://github.com/prtm1908/Music-Generation-LSTM.git
    ```

2. **Setup** the environment:

    ```bash
    pip install -r requirements.txt
    ```

3. **Data Preparation**: Prepare your MIDI dataset or use the provided sample dataset and use the provided notebook to preprocess the MIDI data and train the LSTM model

## Disclaimer:

While the AI-generated music can be fascinating and creative, it's important to acknowledge that the generated content might not always be perfect and may require manual curation. Additionally, the project's aim is to assist in music creation, not to replace human musicians.

Enjoy exploring the world of AI music generation with LSTM! If you have any questions or suggestions, please don't hesitate to open an issue or reach out to the repository maintainers.

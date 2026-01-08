# Swara

Swara is a Python application designed to assist singers and musicians in improving their practice sessions. Built with Tkinter, this app listens to your voice or instrument, analyzes the consistency of your pitch, and provides valuable feedback to help you track your progress over time.

## Key Features

- **Pitch Analysis**: Swara listens to your voice or instrument and evaluates how consistent your pitch is.
- **Feedback Mechanism**: Receive real-time feedback to understand your performance and areas for improvement.
- **Progress Tracking**: Monitor your improvement over time with detailed insights.

## How It Works

1. **Input**: Use your microphone to sing or play an instrument.
2. **Analysis**: Swara processes the audio input and checks the pitch consistency.
3. **Feedback**: Get immediate feedback on your performance.

Swara is a perfect companion for anyone looking to enhance their musical skills, whether you're a beginner or a professional.

## Technical Description

Swara is built using the following technologies and libraries:

- **Python**: The core programming language used for the application.
- **Tkinter**: A Python library for creating the graphical user interface (GUI).
- **Audio Processing**: Swara leverages Python libraries to capture and analyze audio input for pitch consistency.
- **Microphone Integration**: The app uses your system's microphone to capture real-time audio input.

## Architecture

Swara is structured into several key components, each responsible for a specific functionality:

- **`main.py`**: The entry point of the application. It initializes the GUI and orchestrates the overall workflow.
- **`Swara_GUI.py`**: Contains the code for the graphical user interface, built using Tkinter.
- **`Swara_Backend.py`**: Handles the core logic for audio processing and pitch analysis.
- **`Swara_Database.py`**: Manages data storage and retrieval, such as user progress and session history.
- **`compTest.py`**: A utility script for testing and debugging components of the application.

## How to Run

1. Ensure you have Python installed on your system.
2. Install the required dependencies using:
   ```bash
   uv sync
   ```
3. Start the application using the `uvicorn` server for better performance:
   ```bash
   uvicorn main:app --reload
   ```

Swara is designed to be lightweight and user-friendly, making it accessible to musicians of all skill levels.

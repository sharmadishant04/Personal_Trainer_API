# Personal Trainer Assistant

This project is a Python-based personal trainer assistant that leverages the OpenAI GPT-3.5-turbo-16k model to provide workout and nutrition advice. The assistant is designed to help users achieve their fitness goals by offering personalized recommendations and addressing user queries.

## Features

- Provides personalized workout and nutrition advice.
- Uses the OpenAI API for generating responses.
- Waits for the completion of the assistant's run and retrieves the response.
- Logs the steps and the assistant's responses.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/personal-trainer-assistant.git
    cd personal-trainer-assistant
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up environment variables:
    - Create a `.env` file in the root directory of the project.
    - Add your OpenAI API key to the `.env` file:
      ```sh
      OPENAI_API_KEY=your_openai_api_key
      ```

## Usage

Run the script to interact with the personal trainer assistant:

```sh
python personal_trainer_assistant.py

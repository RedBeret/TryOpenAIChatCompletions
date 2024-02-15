# TryOpenAIChatCompletions
# OpenAI API CLI Testing Tool

This tool is designed to provide a simple command-line interface (CLI) for interacting with the OpenAI API. It allows users to test the natural language processing capabilities of OpenAI's models, making it an ideal starting point for developers and enthusiasts looking to explore AI for text completions, answering questions, and more.

## Features

- Easy setup and usage.
- Test interaction with OpenAI's models directly from the command line.
- Customizable bot role for varied response types.
- Designed for educational and testing purposes.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8.13, if you see lines in your IDE after pipenv install check your python version (python --version).
- An OpenAI API key. You can obtain one by signing up at [[OpenAI](https://openai.com/)](https://platform.openai.com/api-keys). (also please be aware of the openai terms and conditions and fees)

## Installation

1. Clone this repository to your local machine or fork it:
   ```
   git clone git@github.com:RedBeret/TryOpenAIChatCompletions.git
   ```
2. Navigate into the cloned repository:
   ```
   cd TryOpenAIChatCompletions
   ```
3. Install the required packages:
   ```
   pipenv install && pipenv shell
   ```

## Configuration

1. Create a `.env` file in the root directory of the project.
2. Add your OpenAI API key to the `.env` file:
   ```
   OPENAI_API_KEY='your_api_key_here'
   Example : OPENAI_API_KEY=AB-CDEFG123456
   ```

## Usage

To use the OpenAI API CLI Testing Tool, follow these steps:

1. Run the script from the command line:
   ```
   python src/openai_cli.py
   ```
2. Enter your prompt when prompted.
3. The AI's response will be displayed in the console.
4. Type 'exit' to quit the tool at any time.

## Customizing the Bot Role

You can customize the bot's role by modifying the `BotRole` variable in the script. The default role is set to a friendly assistant that responds by saying no very nicely to you and asking you to refer to the botrole to change. For more customization, refer to lines 41-47 in the `openai_cli.py` script.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change. Hope you enjoy and star if you like it.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Contact

If you have any questions or feedback, please don't hesitate to reach out.

---

This tool is intended for educational and testing purposes only, providing a quick and easy way to interact with the OpenAI API without setting up a full application.
```

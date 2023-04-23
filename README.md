# Copilot Clone using Python and OpenAI API

This project is a clone of GitHub's Copilot, a tool that uses AI to assist developers in writing code. It is built using Python and the OpenAI API.

## Installation

To use this project, you will need to have Python 3 installed on your system. You will also need to create an account on the [OpenAI API website](https://beta.openai.com/signup/) to get an API key.

1. Clone this repository to your local machine:
```Python

https://github.com/vanshgulati16/Friday.git
```

2. Change into the project directory:
```Python
cd friday
```
3. Install the required packages using pip:
```python
pip install -r requirements.txt
```

4. Create a file named `.env` in the project directory and add your OpenAI API key to it:
```python
OPENAI_API_KEY=your_api_key_here
```

## Usage

To use the Copilot clone, run the following command in the project directory:
```
python friday.py
```
This will start the program and prompt you to enter a code snippet. Once you have entered a code snippet, the program will use the OpenAI API to generate code suggestions based on the input.

## Packages Used

- `python-dotenv`: This package is used to load environment variables from a `.env` file.
- `rich`: This package is used to format the output of the program.
- `openai`: This package is used to interact with the OpenAI API.

## Contributing

If you would like to contribute to this project, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.









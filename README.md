# openai-cli-prompt

Simple CLI prompt for easy I/O with OpenAI's API

## Quickstart

Configure the `working_params` in `main.py`.

```Shell
# Install dependencies
$ pipenv install

# Start the prompt
$ pipenv run python main.py

Prompt:
```

Each completion will save JSON in `completions/` with the parameters, prompt, and completion of the completion.

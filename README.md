# Askmistral
Simple bash script to interact with mistral from the command line.

## Usage
Clone this repo.

Obtain an API key from https://mistral.ai/, create an .env file and set 
`API_KEY=<yourkey>`.

Authorise the file as an executable, e.g.: `chmod +x ./askmistral`.

Run with either `./askmistral <model> -f <filename>` or `./askmistral <model> <your_prompt>`. You can view available models from [mistral.ai](https://docs.mistral.ai/platform/endpoints/).

The model's answer will be displayed on the shell, you can then reply by typing
text directly or pointing to a file containing your answer.

When you stop the program (with `q` when prompted), the conversation will be
saved under `conversation/` and named <current_timestamp>.json

## Misc
TODO
    Allow to resume conversation where left of.

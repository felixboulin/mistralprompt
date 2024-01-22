# Askmistral
Simple batch script to interact with mistralai api from the command line.

## Usage
Clone this repo.
Obtain an API key from https://mistral.ai/, create an .env file and set 
API_KEY=<your API key>
Authorise the file as an exectutable, e.g.: `chmod +x ./askmistral`.

Run with either `./askmistral -f <filename>` or `./askmistral <your_prompt>`. 
The model's answer will be displayed on the shell, you can then reply by typing
text directly or insert a file with your reply.

When you stop the program (with `q` when prompted), the conversation will be
saved under `conversation/` and named <current_timestamp>.json

## Misc
TODO
    Allow to resume conversation where left of.

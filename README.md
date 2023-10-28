# Story_storm

The code is a Streamlit app called "Story Storm" that generates stories based on user input. It uses the langchain library and OpenAI's GPT-3 model to generate the stories. The app allows the user to enter a word, select a voice, and then generates a story using the entered word as a prompt. The generated story is then converted into audio using the Eleven Labs API. Additionally, the code also uses the Replicate API to generate images based on the generated story. The app displays the audio and images to the user. The code also includes some form validation to ensure that the user has entered a word and selected a voice before generating the story.

## Installation

To install the required libraries and dependencies, run the following command:

```console
pip install replicate streamlit python-dotenv elevenlabs langchain openai
```

## Usage

To run the application, use the following command:

```console
streamlit run index.py
```
## Credits :

https://replit.com/@DavidAtReplit via https://spotlight-05-12-2023.util.repl.co/

<p align = center> <img src="images/nansenaidow.png"> </p>

# About nansen
This is a GPT-3.5 based flexible and customizable LLM application that was made for the purpose of assisting with Climate Change and Weather Forecasting fundamentally and broadly for anything that's good for us and our environment. But on the way it has been curated to do more that just that. Have fun with it until your API tokens get exhausted. Use them wisely :)

## How to use it?

Pretty easy I guess you can just [Click Here to wake nansen up](https://sankalpkarthi3-codebot-final-nm9pzk.streamlit.app/)
- Not so simple.
- Go to the side menu and enter down your API key from OpenAI.
- Extend the Settings tab
- Select the Model you need from the dropdown.(`gpt-3.5-turbo` being the most powerful)
- Enter the Summary of prompts as in the number of previous messages to consider while answering you(Your `history` can be customized)
- Temperature - here's the magic, 0 to 1 is the range of randomness, 1 being the highest(recommended by our testing team : `5`)
- Prompt Style decides which side of Nansen you need to see.

## What are the different prompts?

## Example Runs below


## How to run it locally?

- Install the dependancies in the `requirements.txt`.
- Now make the `green_genie.py` available locally.
- Get your Open AI and Cohere API key tokens ready!!
- Now open your terminal and create a `.streamlit` directory in your home(~) directory.
- Now download the `config.toml` file in this repository and add it int the same directory.
- Now you can just use `streamlit run green_genie.py` to run it.
- Most important part of all, if it doesn't work get back to us on sankalpkarthi3@gmail.com or in [LinkedIn](https://www.linkedin.com/in/sankalp-karthi-a4b5b1215)

It's recommended to implement the above in a virtualenvironment (We used `pipenv` for this)

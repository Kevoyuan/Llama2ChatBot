# Llama 2 ChatBot
<p align="left">
    <img width=180 src="logo/llama-144.png">
</p>
This project is a chatbot built with Llama 2 that runs on your local machine, the web application is powerede by Streamlit. 


You can try the Demo with CPU here:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://llama2chatbot.streamlit.app/)

<p align="left">
    <img src="Screenshot.png">
</p>
## Installation

Follow these steps to install and run the chatbot on your local machine:

### 1. Setting Up the Virtual Environment

1. Open a terminal or command prompt.

2. Create a virtual environment using Python's built-in `venv` module with the following command:
    - On macOS and Linux:
    ```bash
    python3 -m venv chatbot
    ```
    - On Windows:
    ```bash
    python -m venv chatbot
    ```
    This command creates a new directory named 'chatbot'. Feel free to choose a different name if you prefer.

3. Create a new conda environment, install CLI app, and activate the environment.

    ```bash
    conda create -n mlc-chat-venv -c mlc-ai -c conda-forge mlc-chat-cli-nightly
    conda activate mlc-chat-venv
    ```

4. Activate the virtual environment with the following command:

    - On macOS and Linux:

        ```bash
        source chatbot/bin/activate
        ```

    - On Windows:

        ```bash
        .\chatbot\Scripts\activate
        ```

    You will know the virtual environment is activated when its name appears in your command prompt.   

### 2. Install the Necessary Packages

Once the virtual environment is activated, install the necessary packages with the following command:

```bash
pip install -r requirements.txt
```

### 3. Run the App
After all the packages have been installed, you can run the app with the following command:

```bash
streamlit run app.py
```

Enjoy interacting with the Llama 2 ChatBot!

## Resource
- [GitHub to deploy LLaMA2 on Replicate](https://github.com/a16z-infra/cog-llama-template)
- [Implementing Locally-Hosted Llama2 Chat UI Using Streamlit](https://medium.com/@daydreamersjp/implementing-locally-hosted-llama2-chat-ui-using-streamlit-53b181651b4e)


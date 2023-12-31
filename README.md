# LLAMA-Local-7b
LLAMA Local is a simple and interactive Streamlit application designed to generate AI responses. It uses the Python bindings for llama.cpp model for language understanding and generation. Users input a prompt, and the application returns a response generated by the model.

# Getting Started
Dependencies
This application requires the following Python libraries:

Streamlit
Langchain
You also need a Python 3.7+ environment.

# Installation
## Clone the repo:

bash

``` 
git clone https://github.com/Druvith/LLAMA-Local-An-AI-response-generator.git
 ```
Install the necessary packages:

```
pip install streamlit langchain
```
``` 
pip install llama-cpp-python
```

Download the GGML version of Llama-7B from huggingface.co and place it in the models directory, which should be in the same directory as your main project files.

## Navigate to the project directory and run the Streamlit application:
``` 
cd PROJECT_NAME
 ```
```
streamlit run app2.py
```

# Usage
After running the application, navigate to the local server address provided in your terminal (usually http://localhost:8501). In the app, you will find a text box where you can enter a prompt. After you submit the prompt, the application will display the AI's response.

# Model Information
The application uses the python bindings for LlamaCpp language model, which is loaded from a local binary file (./models/llama-2-7b.ggmlv3.q4_K_S.bin). Ensure that this file is in the correct location for the application to function.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License
MIT


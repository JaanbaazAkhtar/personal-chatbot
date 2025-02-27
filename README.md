# personal-chatbot
## Steps to set up a personal chatbot like chatGPT

1. Install python in your system.
2. Clone this project.
3. Install the dependencies
    pip install -r ./requirements.txt
4. Download and Install ollama in your system.
5. Open a terminal and then run the following command
    ollama run llama3.3
    where llama3.3 is the name of the model, here you are free to choose any model from ollama.
6. In the app.py file change the value of "MODEL" to the name of the model that you have just installed.
7. Activate your virtual environment.
8. Finally run the project
    streamlit run app.py
9. You can then visit http://localhost:8501, to interact with your model.



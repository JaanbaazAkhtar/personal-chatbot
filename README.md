# Personal Chatbot

A personal chatbot interface built with Streamlit, using Ollama models like `llama3.3`. This guide will help you set up and run your chatbot seamlessly.

## Prerequisites

- Install **Python** on your system.
- Install **Ollama** for running AI models locally.
- Ensure you have **pip** for package management.

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/your-repository/personal-chatbot.git
cd personal-chatbot
```

### 2. Install Dependencies
```sh
pip install -r requirements.txt
```

### 3. Install & Run Ollama

Download and install **Ollama** from [Ollama's official website](https://ollama.ai/).
Once installed, run the following command to start your model:
```sh
ollama run llama3.3
```
*(You can replace `llama3.3` with any model available in Ollama.)*

### 4. Configure the Model
Edit the `app.py` file and update the `MODEL` variable with the name of the model you installed.

### 5. Activate Virtual Environment (Optional but Recommended)
If you're using a virtual environment, activate it:
```sh
source venv/bin/activate  # macOS/Linux
```

### 6. Run the Chatbot
```sh
streamlit run app.py
```

### 7. Access the Chatbot
Once the server starts, open your browser and go to:
```sh
http://localhost:8501
```

## Usage

- Type your queries in the chat interface.
- The chatbot will respond based on the selected AI model.
- Modify `app.py` to customize the chatbot behavior.

## Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.


Custom LLM Development 

## Setup

1. Create a `.env` file and add there your OpenAI API key. Its content should be something like:

```bash
OPENAI_API_KEY="sk-..."
```

2. Create a local virtual environment, for example using the `venv` module. Then, activate it.

```bash
python -m venv venv
source venv/bin/activate
```

3. Install the dependencies.

```bash
pip install -r requirements.txt
```

4. Launch the Gradio app.

```bash
python app.py
```

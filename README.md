# Chat with PDF

A **Streamlit-based PDF chatbot** that uses **EmbedChain** and **OpenAI embeddings** to let you ask questions about any PDF document.

---

## Features

- Upload a PDF and add it to a knowledge base.
- Ask questions about the PDF and get instant answers.
- Built with **Streamlit** for a simple web interface.
- Uses **OpenAI LLM** for natural language understanding.
- Vector database powered by **Chroma** for efficient document embeddings.

---

## Setup

1. **Clone the repository and set up environment**
```bash
# Clone the repository
git clone https://github.com/Ami-Khokhar/Chat_with_x.git
cd Chat_with_x

# Create a virtual environment (optional but recommended)
python -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
# If requirements.txt doesn’t exist:
pip install streamlit embedchain python-dotenv

# Set your OpenAI API key
# Create a .env file in the project root:
echo "OPENAI_API_KEY=your_openai_api_key_here" > .env

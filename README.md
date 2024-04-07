
# Chat with MySQL Database Using LangChain 🗣️📊

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-Integrated-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## Introduction 📜
This project integrates LangChain with a MySQL database to enable conversational interactions with the database. It leverages natural language processing (NLP) to query and manipulate database information using simple, conversational language. The project includes a custom Python script for extended functionality, integration with the Gemini API for advanced NLP tasks, a Jupyter notebook guide for setup and interaction, and a Streamlit application for a user-friendly interface.

## Table of Contents 📚
- Introduction
- Getting Started
  - Dependencies
  - Installation
- Usage
  - Configuration
  - Running the Application
- Features
- Documentation
  - Custom Python Script
  - Gemini API Integration
  - Jupyter Notebook Guide
  - Streamlit Application
- Examples
- Troubleshooting
- Contributors
- License

## Getting Started 🚀

### Dependencies
This project requires the following dependencies:
- Python 3.9 or higher
- LangChain
- Streamlit
- pandas
- MySQL database
- OpenAI API key
- Google API key (for Gemini API integration)

### Installation
To set up the project environment:
1. Clone the repository to your local machine.
2. Install the required Python packages using `pip install -r requirements.txt`.

## Usage  🛠️

### Configuration
Before running the application, configure the following environment variables:
- `OPENAI_API_KEY`: Your OpenAI API key for accessing GPT models.
- `GOOGLE_API_KEY`: Your Google API key for the Gemini API integration.
- Database connection details in the respective scripts (`custom_tool.py`, `gemini.py`, and `sql_app.py`).

### Running the Application
- **Custom Python Script**: Execute `python custom_tool.py` to use the extended functionality.
- **Gemini API Integration**: Run `python gemini.py` for tasks involving the Gemini model.
- **Jupyter Notebook Guide**: Open `mysql.ipynb` with Jupyter Notebook to follow the step-by-step guide.
- **Streamlit Application**: Launch the Streamlit app with `streamlit run sql_app.py`.

## Features ✨
- Conversational interaction with MySQL databases using natural language.
- Integration with the Gemini API for advanced NLP capabilities.
- Custom Python script for extended functionality and integration with external tools.
- Streamlit application for a graphical interface to the database.

## Documentation 📖
Refer to the following documentation for more information on the technologies and libraries used:
- [LangChain](https://langchain.com)
- [Streamlit](https://docs.streamlit.io)
- [Pandas](https://pandas.pydata.org/docs/)
- [MySQL](https://dev.mysql.com/doc/)

## Examples 📝
Examples of usage will be provided in the respective script files, demonstrating how to interact with the database, integrate external tools, and utilize the Gemini model.

## Troubleshooting 🔧
For issues related to environment setup, API keys, or database connections, refer to the respective service's documentation. For more specific problems, consider opening an issue in the project repository.

## Contributors 👥
To contribute to this project, please fork the repository and submit a pull request.

## License 📄
This project is released under the MIT License. See the LICENSE file for more details.

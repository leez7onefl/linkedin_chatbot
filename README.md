# Leonard's CV assistant

Leonard's Assistant is a Streamlit application designed to facilitate easy information retrieval from PDF documents stored in a GitHub repository. The application leverages OpenAI's GPT models and Pinecone's vector database to provide insightful responses to user queries.

## Features

- Extracts text from PDF documents.
- Summarizes and stores documents in a vector database.
- Utilizes GPT models to generate responses to user queries.
- Supports different interaction parameters such as creativity, randomness, and frequency penalty.

## Repository Structure

- **CV_Leonard_Gonzalez_ENG.pdf**: A document that might contain a CV pertinent to Leonard Gonzalez.
- **Leonard_Gonzalez_Memoire_M1_Transforming...pdf**: A essay document related to Leonard Gonzalez.
- **Léonard_Gonzalez_AssessFirst.pdf**: An assessment document of Leonard Gonzalez.
- **Reddit_Awards.pdf**: Document listing Reddit awards.
- **TOEIC_mars_2024.pdf**: TOEIC documentation possibly dated March 2024.
- **cover_letter_Leonard_Gonzalez_ENG.pdf**: A cover letter belonging to Leonard Gonzalez.
- **main.py**: The main script for running the application.
- **requirements.txt**: Contains the Python dependencies needed for the project.

### Folders

- **.devcontainer/**: Contains configuration for development containers.
- **.streamlit/**: Configuration files for the Streamlit app.
- **Documents/**: Directory for storing raw document files.
- **env/**: Directory presumably for environment configurations.
- **myenv/**: Custom environment setup.

## Prerequisites

- Python 3.6 or later
- Installation of dependencies from `requirements.txt`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/leonards-assistant.git
    cd leonards-assistant
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Prepare `.env` files with required API keys and configurations.

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run main.py
    ```

2. Use the sidebar to adjust model parameters and interact with the assistant.

3. Query the assistant by typing into the chat input field.

## Environment Variables

Ensure you set up environment variables in `.env` and `keys.env` files. Required keys include:

- `OPENAI_API_KEY`
- `PINECONE_API_KEY`
- `PINECONE_INDEX_NAME`
- `GITHUB_TOKEN`
- `GITHUB_REPO`
- `GITHUB_BRANCH` (optional)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

## Contact

For questions or feedback, please reach out to [leonard.gonzlez@outlook.fr](mailto:leonard.gonzlez@outlook.fr).

---

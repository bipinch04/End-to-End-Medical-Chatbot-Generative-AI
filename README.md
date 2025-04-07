# End-to-End Medical Chatbot with Generative AI

This project implements an end-to-end medical chatbot powered by Generative AI. The chatbot is designed to assist users with medical inquiries by providing accurate and context-aware responses. It leverages state-of-the-art AI models and integrates seamlessly with a backend API for enhanced functionality.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

The medical chatbot is built using modern AI technologies, including natural language processing (NLP) and generative AI models. It is designed to:
- Understand user queries in natural language.
- Provide accurate and contextually relevant medical information.
- Offer a user-friendly interface for interaction.

---

## Features

- **Generative AI Integration**: Utilizes advanced AI models for generating responses.
- **Medical Knowledge Base**: Trained on a dataset of medical information.
- **Interactive Chat Interface**: User-friendly interface for seamless interaction.
- **Scalable Backend**: API-driven architecture for scalability.
- **Customizable**: Easily extendable to include additional features or integrate with external systems.

---

## Project Structure

```
End-to-End-Medical-Chatbot-Generative-AI/
├── src/
│   ├── models/          # AI models and training scripts
│   ├── api/             # Backend API implementation
│   ├── utils/           # Utility functions and helpers
│   ├── config/          # Configuration files
│   └── app.py           # Main application entry point
├── data/
│   ├── training_data/   # Dataset for training the AI model
│   └── processed_data/  # Preprocessed data
├── tests/               # Unit and integration tests
├── docs/                # Documentation and resources
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── LICENSE              # License information
```

---

## Setup and Installation

STEPS:
Clone the repository

Project repo: https://github.com/

STEP 01- Create a conda environment after opening the repository
conda create -n medibot python=3.10 -y
conda activate medibot

STEP 02- install the requirements
pip install -r requirements.txt

Create a .env file in the root directory and add your Pinecone & openai credentials as follows:
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# run the following command to store embeddings to pinecone
python store_index.py
# Finally run the following command
python app.py
Now,
open up localhost:

Techstack Used:
Python
LangChain
Flask
GPT
Pinecone

## Usage

1. Start the application using the command above.
2. Access the chatbot interface via the provided URL (e.g., `http://localhost:5000`).
3. Interact with the chatbot by typing your medical queries.

---

## Dependencies

The project uses the following key dependencies:
- **Flask**: For building the backend API.
- **Transformers**: For leveraging pre-trained generative AI models.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For additional machine learning utilities.

Refer to `requirements.txt` for the complete list of dependencies.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out with any questions or suggestions!
   
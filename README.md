
# Cold Email Generator

## Overview

The **Cold Email Generator** is a Python-based tool designed to assist service companies in crafting personalized cold emails to potential clients. By analyzing job listings from a target company's careers page, the system identifies key requirements and matches them with relevant portfolio items, generating tailored emails that highlight the service company's strengths.

---

## Features

- **Automated Job Listing Extraction**: Scrapes job postings from a provided URL.
- **Portfolio Matching**: Identifies relevant portfolio items based on job requirements.
- **Personalized Email Generation**: Crafts customized emails that align with the job descriptions.
- **User-Friendly Interface**: Simple command-line interface for ease of use.

---

## Technologies Used

- **Python**: Core programming language.
- **Langchain**: For natural language processing and email generation.
- **ChromaDB**: Vector database for storing and retrieving portfolio items.
- **Streamlit**: For building the user interface (if applicable).
- **Groq**: For efficient querying of job listings.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Shahrukhzx/cold-email-generator.git
   cd cold-email-generator
   ```

2. Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the application:

   ```bash
   python app/main.py
   ```

2. Input the URL of the target company's careers page when prompted.

3. The system will process the job listings, match relevant portfolio items, and generate a personalized cold email.

---

## File Structure

```
cold-email-generator/
├── .gitignore         # Specifies files and directories to be ignored by Git (e.g., 
├── requirements.txt   # Python dependencies for the project
├── app/               # Directory containing the main application files
│   ├── main.py        # Main application entry point
│   ├── chains.py      # Logic for chaining processes
│   ├── portfolio.py   # Portfolio item management
│   ├── utils.py       # Utility functions
│   ├── vectorstore/   # Directory for vector database (ignored by Git)
│   └── resource/      # Additional resources inside the app folder
```

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

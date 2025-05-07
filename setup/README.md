# Nos Hackathon

## Authors

This project was developed by:

Afonso Santos

André Ferreira

João Chaveiro

José Mariano

# [Nos Gen Ai Hackathon]

[![Project Status](https://img.shields.io/badge/status-in%20development-green)](https://www.repostatus.org/#wip)

[![GitHub Contributors](https://img.shields.io/github/contributors/JoseMariano247)](https://github.com/JoseMariano247)
[![GitHub Contributors](https://img.shields.io/github/contributors/figipef)](https://github.com/figipef)
[![GitHub Contributors](https://img.shields.io/github/contributors/0tilarr)](https://github.com/0tilarr)
[![GitHub Contributors](https://img.shields.io/github/contributors/Formiga03)](https://github.com/Formiga03)

[![License](https://img.shields.io/badge/license-[Your%20License]-blue.svg)](LICENSE) A brief and engaging description of your project. What problem does it solve? What are its key features? Keep it concise and interesting.

## Table of Contents

- [About](#about)
- [How We Did It](#how-we-did-it)
- [Production Steps](#production-steps)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Collaborators](#collaborators)
- [Contact](#contact)

## About

Given a .pdf file with sensative information we extract the text from the whole file and throught a gemini prompt redact it basing ourselves in the EU regulations on the "Regulation (EU) 2016/679 (General Data Protection Regulation)".

## How We Did It

This section should detail the development process and the technologies used.

- **Technology Stack:** List the main programming languages, frameworks, libraries, and tools you utilized.
  ```
  - Language: Python;
  - Libraries: PyMuPDF, fitz;
  - Tools: Google Colab, GitHub.
  ```
## Production Steps

In order to develop our solution for the problem, we split the task in 4 parts:

1.  **Environment setup on GitHub and Google Colab;**
2.  **PDF Reader Function;** 
3.  **Prompt Developement;** 
4.  **Prompt Application on the output of the Reader Function;**
5.  **Code Testing.**

## Getting Started



### Prerequisites

List any software or tools that need to be installed before they can work on the project. Be specific with versions if necessary.

- [Node.js](https://nodejs.org/) (version >= 16.0.0)
- [Python](https://www.python.org/) (version >= 3.9)
- [Docker](https://www.docker.com/)
- [Specific database system]

### Installation

Provide clear, step-by-step instructions on how to get the project running on a local machine.

1.  Clone the repository:
    ```bash
    git clone [https://github.com/](https://github.com/)[your-github-username]/[your-repo-name].git
    ```
2.  Navigate to the project directory:
    ```bash
    cd [your-repo-name]
    ```
3.  Install dependencies (example for Python):
    ```bash
    pip install -r requirements.txt
    ```
    (or for Node.js)
    ```bash
    npm install
    # or
    yarn install
    ```
4.  Set up environment variables. You might want to refer to an example file (e.g., `.env.example`) and explain which variables need to be configured.
5.  Run any necessary setup or initialization scripts:
    ```bash
    # Example for database migrations
    python manage.py migrate
    # Example for building frontend assets
    npm run build
    ```

## Usage

Explain how to use the project. Provide examples of common use cases and how to interact with the application or library. Include code snippets or screenshots if they help illustrate the functionality.

```python
# Example usage
from your_project import some_function

result = some_function(input_data)
print(result)
```


## Collaborators

List the main collaborators on the project. You can include their GitHub usernames and optionally a brief description of their contributions.

- [GitHub figipef](https://github.com/figipef) - PDF file reader fucntion
- [GitHub 0tilarr](https://github.com/0tilarr) - Prompt development
- [GitHub JoseMariano247](https://github.com/JoseMariano247) - Prompt application code
- [GitHub Formiga03](https://github.com/Formiga03) - ReadMe file and slides


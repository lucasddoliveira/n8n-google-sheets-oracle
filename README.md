# n8n-google-sheets-oracle

This n8n workflow is designed to analyze and make changes to a Google Sheets spreadsheet based on user requests, directly through natural language commands.

## Features

- **Query Employee Data**: Retrieve information about employees, such as their skills, locations, or vehicles.
- **Update Employee Data**: Modify employee details, such as adding new skills, updating locations, or changing vehicle information.
- **Natural Language Processing**: Interact with the workflow using simple, human-readable commands.

## Examples

### Querying Data
- **Who knows JavaScript? List 3.**
  - *Response*: Daniel Souza, Paulo Patricio, and Luiza Silva know JavaScript.
  
- **Who lives in Belo Horizonte and knows PostgreSQL?**
  - *Response*: Camila Rocha lives in Belo Horizonte and knows PostgreSQL.
  
- **Everton Lima drives what car?**
  - *Response*: Everton Lima drives a Chevrolet Onix.
  
- **What skills does Patricio have?**
  - *Response*: Patricio has skills in Python.
  
- **List everyone in the database.**
  - *Response*: 
    - Amanda Pereira
    - Bruno Santos
    - Camila Rocha
    - Daniel Souza
    - Everton Lima
    - Paulo Patricio
    - Jefferson Prates
    - Daniel Ferreira
    - Luiza Silva

- **What are the cities of the workers?**
  - *Response*: 
    - São Paulo: Amanda Pereira, Paulo Patricio
    - Rio de Janeiro: Amanda Pereira, Bruno Santos
    - Belo Horizonte: Bruno Santos, Camila Rocha, Jefferson Prates
    - Porto Alegre: Daniel Souza, Daniel Ferreira
    - Curitiba: Everton Lima
    - New York: Luiza Silva

### Updating Data
- **Luiza Silva now lives in Medellin.**
  - *Response*: Luiza Silva now lives in Medellin.
  
- **Camila Rocha now drives a Tesla.**
  - *Response*: Camila Rocha now drives a Tesla.
  
- **Add N8N to Paulo Patricio's skills.**
  - *Response*: Added N8N as a skill for Paulo Patricio.

## How It Works

1. **Input**: The user provides a natural language command (e.g., "Who knows JavaScript?").
2. **Processing**: The workflow parses the command, queries the Google Sheets spreadsheet, and retrieves the relevant data.
3. **Output**: The workflow responds with the requested information or confirms the update made to the spreadsheet.

---

**Note**: Replace placeholders (e.g., spreadsheet ID, credentials) with your actual data during setup.

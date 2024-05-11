# seek-saral
realtime scheme , govt notice , press release chat bot with llm and RAG integration

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/isurulkh/rag-application-gemini.git
    ```

2. Navigate to the project directory:

    ```bash
    cd rag-application-gemini
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

5. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2. Open your browser and go to `http://localhost:8501`.

3. [Provide any additional usage instructions].

## Configuration

### Environment Variables

- `GOOGLE_API_KEY`: Obtain a Google Generative AI API key from the [Google Cloud Console](https://console.cloud.google.com/) and set it as an environment variable.

    ```bash
    export GOOGLE_API_KEY=your_google_api_key
    ```


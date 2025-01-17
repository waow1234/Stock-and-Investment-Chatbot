# Stock and Investment Chatbot
## Overview and Use Cases
The Stock and Investment Chatbot is designed to assist users in obtaining information about stock prices and financial data. It also provides investment recommendations and analysis based on user queries. The chatbot can answer questions, fetch real-time stock prices, and compare multiple stock symbols.

### Use Cases
- **Query Stock Information**: Users can request current stock prices for individual symbols.
- **Compare Stock Prices**: Users can compare prices of multiple stock symbols.
- **Answer Financial Questions**: Users can ask general financial or stock-related questions to receive contextual answers.
## Technologies and Tools
- **Hugging Face Transformers**: Used to create the question-answering model and generate contextual answers.
- **SpaCy**: Utilized for natural language processing tasks (if applicable).
- **Alpha Vantage API**: Provides real-time stock prices and financial data.
- **Generative AI**: Used to create sample data and train models (if applicable).

## Setup and Run

1. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

2. **Configure API Key**:
    - Obtain an API Key from [Alpha Vantage](https://www.alphavantage.co/support/#api-key) and set it in the `.env` file.

3. **Run the App**:
    ```bash
    python app.py
    ```

4. **Access the App**:
    Open your web browser and go to the URL provided by Streamlit to interact with the chatbot.

## Notes
- Ensure that you have Python 3.6+ installed.
- Update the `.env` file with your actual API key.
  
## Embedding Techniques

Embedding is a technique to convert textual data into numerical vectors that represent the semantic meaning of words or phrases. For this project, BERT (Bidirectional Encoder Representations from Transformers) is used to create embeddings. BERT transforms text into vectors that capture contextual relationships between words.


## Hugging Face Components Used
Question Answering Pipeline: Utilizes the distilbert-base-cased-distilled-squad model to answer user questions based on provided context.

## API Usage
- **Alpha Vantage API**: Used to fetch stock price data. You need to sign up and obtain an API Key from the Alpha Vantage website.

## Instructions for Running and Testing MVP
1. **Install Dependencies**:
    ```bash
    pip install transformers requests flask python-dotenv
    ```
2. **Set Up API Key**:
    - Sign up and obtain an API Key from Alpha Vantage.
    - Set the API Key in the code.

3. **Run the Chatbot**:
    - Run the main script to start the Chatbot.
    - Test various functions by sending questions to the Chatbot through the Command Line or a supported platform.

## User Interface and Usability (UI/UX)
The current implementation is a web-based application using Flask and Bootstrap for a responsive design. The UI allows users to:
    -Ask questions about stock and investment.
    -Get stock information by providing a stock symbol.
    -Compare multiple stocks by entering their symbols.

## Future Enhancements
Enhanced UI: Improve the user interface for better user experience.
Additional APIs: Integrate more APIs for broader financial data coverage.
Advanced Analytics: Implement advanced data analytics features for deeper market insights.

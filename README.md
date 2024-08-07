# Ai Chatbot (London Hotel Chatbot)

This repository contains the code for the London Hotel Chatbot, a web-based application that provides information about the Landon Hotel. The chatbot is built using Flask for the backend and a simple HTML/CSS/JavaScript frontend. It leverages OpenAI's language model to generate responses to user queries about the hotel.

## Features

- Provides information and advice exclusively about the Landon Hotel.
- Rejects queries not related to the Landon Hotel with a polite response.
- Simple and intuitive user interface for interacting with the chatbot.

## Files in the Repository

- `chatbot.py`: The main Flask application file that handles the backend logic.
- `index.html`: The frontend HTML file that contains the user interface for the chatbot.

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- Python 3.6+
- Flask
- An OpenAI API key

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Xlaton25/AI-Chatbot.git
    ```
    
    ```bash
    cd Ai-Chatbot-London-Hotel-Chatbot
    ```

2. Install the required Python packages:

    ```bash
    pip install flask langchain-openai
    ```

3. Set up your OpenAI API key:

    Replace `'API HERE'` in `chatbot.py` with your actual OpenAI API key.

4. Run the application:

    ```bash
    python chatbot.py
    ```

5. Open your browser and navigate to `http://127.0.0.1:5000` to use the chatbot.

## Usage

- Enter your query related to the Landon Hotel in the input box and click 'Send' or press 'Enter'.
- The chatbot will respond with information or advice about the hotel.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://openai.com/) for the language model
- [Flask](https://flask.palletsprojects.com/) for the web framework
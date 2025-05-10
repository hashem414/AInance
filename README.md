Jordan Mall Financial Assistant Chatbot
Welcome to the Jordan Mall Financial Assistant! This chatbot helps you analyze transaction data from malls in Jordan. You can ask questions about transaction patterns, failures, top malls, and more. It uses GPT-4o-mini to provide intelligent responses based on a sample of retail transaction data.
Features
•    Ask about transaction patterns, failed transactions, or mall performance.
•    Uses GPT-4o-mini model to answer based on a dataset of Jordanian mall transactions.
•    Provides quick and concise responses from the sample data provided.
How it Works
1.    The chatbot processes the transaction data (stored in a CSV file) and converts it into a string format.
2.    User queries are sent to the GPT-4o-mini model with the dataset as context.
3.    The chatbot returns answers related to transaction trends and other performance data.
Running Locally
The Gradio interface for this chatbot runs at:
 https://c7760a666ea61f4b33.gradio.live/
You can interact with the model directly through the web interface.
Usage
Simply type your question in the input box (e.g., "Show me all failed transactions at Z Mall last week?" or "Which branch has the highest transaction failure rate?") and the chatbot will provide a response based on the sample data.
Link to Chatbot in Action
To learn more about how the chatbot works, you can explore the demo link:  https://drive.google.com/file/d/10i6nYnxqGI4-bm2m6xmizBtvCVNrpiUU/view?usp=sharing 


Requirements
•    Python 3.x
•    Gradio
•    Requests library
•    A valid API key for the GPT model
How to Run Locally
1.    Clone this repository.
2.    Install the required dependencies:
3.    pip install gradio pandas requests
4.    Update the API_KEY and API_URL in the script with your valid API credentials.
5.    Run the Python script:
6.    python chatbot.py
7.    Open the link provided in the terminal to interact with the chatbot.
 

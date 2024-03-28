DocGPT - Your Intelligent Document Analysis and Data Science Chatbot
Welcome to the official GitHub repository for DocGPT, your go-to tool for advanced document analysis and data science tasks. DocGPT is powered by OpenAI's Language Model and can analyze documents in various formats, including PDF, TXT, and CSV.

What Can DocGPT Do?
DocGPT is a versatile chatbot with the following key features:

Document Analysis: Extract valuable insights and information from PDF and TXT documents with ease.
Data Science: Perform data analysis and execute data science prompts with CSV files, making it perfect for researchers and data professionals.
OpenAI Integration: DocGPT uses OpenAI's powerful language model and requires an OpenAI API key for full functionality.
Getting Your OpenAI API Key
To use DocGPT with full capabilities, you'll need an OpenAI API key. Here's how to obtain one:

Visit OpenAI's website and create an account.
Navigate to the API section and follow the instructions to generate your API key.
Once you have your key, you can proceed to configure DocGPT.
Installation and Execution
Follow these steps to clone, set up, and run DocGPT:

Clone this repository to your local machine using Git:

https://github.com/NirmalNagaraj/DocGPT.git
Navigate to the project directory:

cd DocGPT
Install the required Python packages using pip:

pip install -r requirements.txt
Create a .env file by copying the .env.example file and replace YOUR_OPENAI_API_KEY with your actual OpenAI API key: (or) Create a .env file and include this line

OPENAI_API_KEY = "YOUR API KEY "
Run the application using Streamlit:

 streamlit run app.py
Open your web browser and access the DocGPT interface at http://localhost:8501.

That's it! You're now ready to use DocGPT for document analysis and data science tasks.

# Document Comparison App 📝

A Streamlit application for comparing documents using Langchain and OpenAI API. This app enables users to upload a master policy document alongside one or more client policy documents. It identifies missing key points and offers suggestions for updating client documents to better align with the master document.

## Features ✨

- **User Authentication** 🔐: Secure signup and login process.
- **Document Upload** 📁: Upload master and client policy documents in .docx format.
- **Comparison Analysis** 📊: Automatically identifies missing key points from the master document in client documents.
- **Suggestions for Improvement** 💡: Provides actionable suggestions to update client documents using advanced language processing.
- **Downloadable Updates** ⬇️: Easily download the modified client documents with highlighted changes.

## Technologies Used 🛠️

- **Streamlit**: A powerful framework for creating web applications.
- **LangChain**: For advanced document comparison and suggestions.
- **OpenAI API**: Utilized for natural language processing capabilities.
- **Python-docx**: For reading and manipulating .docx files.

## Installation ⚙️

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/your-username/policy-comparison-app.git
   cd policy-comparison-app

2. **Install the required Python packages listed in requirements.txt**
streamlit==1.15.0
langchain==0.0.200
openai==0.27.0
python-docx==0.8.11
bcrypt==3.2.0
pandas==1.5.3

3. **Set your OpenAI API key in the application code (DC and document.py)**
os.environ['OPENAI_API_KEY'] = "Enter API Key"

4. **Run the Streamlit app**
   streamlit run DC.py

## Usage 📚

1. Sign up for a new account or log in to your existing account.
2. Upload your master policy document and the client policy documents you wish to compare.
3. Review the results to see missing key points and suggestions for updates.
4. Download the updated client documents for your records.

## Acknowledgments 🙏

-Developed using Streamlit, a powerful framework for creating web applications.
-Utilizes LangChain for advanced document processing and comparison.
-Leverages the OpenAI API for enhanced natural language processing capabilities.

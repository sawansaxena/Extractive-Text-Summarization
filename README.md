# Extractive-Text-Summarization

Text summarization in an important application of Natural Language Processing which aims to procude a concise summary of the original text while retaining key information. This project focuses on one of the two methods of summarizing text, that is Extractive Summarization.

I have used Flask API to integrate my python script with a web application. Deployment is done on Heroku cloud platform. Following is the link to the web application: https://nlp-extractive-summary.herokuapp.com  

# Prerequisites
You must have following python libararies installed on your machine. Please refer to requirements.txt file for details.
- Flask (for creating web application)
- NLTK (for natural language processing)
- Networkx (for using graph based algorithms)

# Project Structure
The projects has following major parts:
1. app.py : Contains Flask APIs that receive inputs through GUI, calls the main python script for processing and returns the output.
2. textsummarizer.py : Contains python code to generate text summary from original text.
3. templates : Contains HTML files that allow user to interact with the application.

# Running the Project
1. Open Ananconda command prompt and move to your project home directory.
2. Run app.py using below command to start Flask API
python app.py
3. Navigate to the localhost to view the application home page. Localhost:  http://127.0.0.1:5000/ or http://localhost:5000
4. Enter the text to summarize in the texbox and hit Summarize button.
5. If everything goes well, you should be able to see the summarized version of the text on the results page.




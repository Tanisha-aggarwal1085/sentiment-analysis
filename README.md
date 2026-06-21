Sentiment Analysis App
A simple web application built using Python, Flask, and TextBlob that analyzes the sentiment of user-entered text and classifies it as Positive, Negative, or Neutral.
Features
User-friendly web interface
Detects sentiment of text
Displays:
Positive 😊
Negative 😔
Neutral 😐
Shows polarity score
Built using Flask and TextBlob
Technologies Used
Python
Flask
TextBlob
HTML/CSS
Project Structure
Sentiment_Analysis/
│
├── app.py
├── templates/
│   └── index.html
├── screenshots/
├── README.md
Installation
Step 1: Clone Repository
git clone https://github.com/your-username/sentiment-analysis.git
Step 2: Open Project Folder
cd sentiment-analysis
Step 3: Install Required Libraries
pip install flask textblob
Run the Application
Open in Browser
http://127.0.0.1:5000
Example Inputs
Input Text	Result
I love this project	Positive 😊
This is terrible	Negative 😔
Today is Monday	Neutral 😐
Output
The application displays:
Sentiment type
Polarity score
Example:
Positive 😊
Polarity: 0.5
How Sentiment Analysis Works
TextBlob analyzes the text and gives a polarity value:
Polarity Score	Meaning
Greater than 0	Positive
Less than 0	Negative
Equal to 0	Neutral
Screenshots
Positive Sentiment Output
Negative Sentiment Output
Neutral Sentiment Output
Flask Terminal Output
Future Improvements
Add modern UI design
Add speech input
Add sentiment charts
Deploy online using Render or Vercel
Author
Tanisha Aggarwal
B.Tech CSE
Amity University

License
This project is for educational and internship purposes.

python app.py
Open in Browser
http://127.0.0.1:5000

# AI-Powered Phishing Detection System
## Introduction
### Project Overview:
This project was designed to do the following:
1.	Analyze email text content.
2.	Extract and evaluate URLs.
3.	Classify emails as phishing or legitimate 
4.	Provide real-time predictions through an interactive web interface.

### Objectives:
By completing this project, I learnt the following:
1.	To detect phishing emails using machine learning techniques.
2.	To analyze both email text and URLs for suspicious patterns.
3.	To build an interactive and user-friendly interface. 
4.	To improve accuracy using labeled phishing datasets.
5.	To demonstrate practical application of AI in cybersecurity.

### Features:
1.	Email Body Analysis: Uses text processing to identify phishing patterns.
2.	URL Scanning: Extracts and evaluates URLs within the email to detect malicious links.
3.	Machine Learning: Trained with labeled phishing data to make predictions on email content.
4.	Interactive UI: Built with Streamlit for real-time predictions.

## Technologies Used
1.	Python: Core programming language 
2.	Streamlit: Web interface for user interaction 
3.	scikit-learn: Machine learning model building 
4.	pandas: Data manipulation and preprocessing 
5.	nltk: Natural language processing 
6.	Requests: HTTP requests for URL analysis 
7.	BeautifulSoup: Web scraping and URL inspection

## Installation and Project Setup
### Prerequisites:
1.	Python 3.9+
2.	VS Code
3.	Git 
4.	4GB RAM minimum
5.	Windows, macOS, or Linux

### Step 1: Create Project
Within the terminal, I created the project.
Commands Used
cd onedrive
cd desktop
mkdir Phishing_Detection_System
cd Phishing_Detection_System

 
Screenshot of Output
 <img width="940" height="375" alt="image" src="https://github.com/user-attachments/assets/08f5f239-17d9-4cfd-83f7-7c492e2821c7" />

Figure 1: Create Project

### Step 2: Clone Repository 
I then cloned the following repository in the created folder. 

Commands Used
git clone https://github.com/GauravGhandat-23/AI-Powered-Phishing-Detection-System 

Screenshot of Output

 <img width="940" height="247" alt="image" src="https://github.com/user-attachments/assets/be1b41f1-2982-4199-96cb-adbd35f0cd1e" />

Figure 2: Clone Repository

 
### Step 3: Navigate to the Project
Commands Used
cd AI-Powered-Phishing-Detection-System

Screenshot of Output
 <img width="940" height="513" alt="image" src="https://github.com/user-attachments/assets/9ea24c39-67ed-476e-bf61-d700d06b678b" />

Figure 3: Project Navigation

### Step 4: Create and Activate Virtual Environment
I created the virtual environment to isolate project dependencies from my system Python.

Commands Used
python -m venv venv
venv\Scripts\activate

 
Screenshot of Output
 <img width="940" height="148" alt="image" src="https://github.com/user-attachments/assets/2af420df-6346-4aa0-8fae-5a0c19a15686" />

Figure 4: Virtual Environment

### Step 5: Install the Dependencies
here the following was installed: (along with 40+ other packages)
1.	pandas
2.	scikit-learn
3.	streamlit
4.	nltk
5.	beautifulsoup4
6.	numpy
7.	scipy 

Commands Used
pip install -r requirements.txt

Screenshot of Output
 <img width="940" height="342" alt="image" src="https://github.com/user-attachments/assets/ccfec4da-24d5-41b8-a72b-97832ff11afe" />
<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/a8dd14bc-0c4f-4873-a3a3-6e7fb470d79a" />

Figure 5: Installed Dependencies

### Step 6: Launch the Application 
1.	Here I launched the application, then pressed enter.
2.	http://localhost:8501/ opened in a web browser.

Commands Used
streamlit run phishing_detection.py

Screenshot of Output
 <img width="940" height="287" alt="image" src="https://github.com/user-attachments/assets/6b1f2223-0eab-47df-92c0-c0eec45c56a3" />
<img width="569" height="597" alt="image" src="https://github.com/user-attachments/assets/26d39f38-9826-4959-95a7-f48611618cd8" />

Figure 6: Launched Application

 
## Implementation 
### Step 1: Test a Phishing Email
Within the browser, I entered the following in the “Enter the Email Body to Check:” body.

Text Entered
Congratulations! You've won a $1000 gift card. Click here to claim your prize: http://phishing.com

Screenshot of Output
 <img width="648" height="275" alt="image" src="https://github.com/user-attachments/assets/b8b6c2d8-1a14-4ab7-860a-e2f0d11f3f98" />

Figure 7: Phishing Email

### Step 2: Test a Safe Email
Within the browser, I entered the following in the “Enter the Email Body to Check:” body.

Text Entered
Hi there, this is a reminder about ort team meeting tomorrow at 2 PM in Conference Room B. Please bring your project updates.

 
Screenshot of Output
 <img width="546" height="349" alt="image" src="https://github.com/user-attachments/assets/2eb1595b-3e7e-4d07-b1a3-876460d56a00" />

Figure 8: Safe Email

### Step 3: Test a Sophisticated Email
Within the browser, I entered the following in the “Enter the Email Body to Check:” body.

Text Entered
Sophisticated
Hello Andrey,

I hope this email finds you well. I'm reaching out from IT regarding 
mandatory security updates. We've detected unusual activity on your account.

Please use this secure link: https://company-portal-secure.com/login

Best regards, IT Security Team

 
Screenshot of Output
 <img width="646" height="358" alt="image" src="https://github.com/user-attachments/assets/069bb60a-e118-4969-b02b-abab3e6317f1" />

Figure 9: Sophisticated Email

## References 
(Andycarsan, 2025)

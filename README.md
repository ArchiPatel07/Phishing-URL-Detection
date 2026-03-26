Name: Patel Archiben Timirbhai
📌 Project Overview
This project is a simple machine learning based system that checks whether a given URL is safe or a phishing link.
Phishing is a type of cyber attack where fake websites are created to trick users into entering sensitive information like passwords, OTPs, or bank details.
The main idea of this project is to analyze the structure of a URL and predict whether it is legitimate or suspicious. The program runs completely in the command line, so it does not require any graphical interface.
⚙️ Features
Detects phishing and safe URLs
Uses Machine Learning (Logistic Regression)
Extracts useful features from URLs
Includes trusted website checking (like YouTube, Google, etc.)
Takes real-time user input
Runs fully in terminal (CLI based)
🛠️ Technologies Used
Python
pandas
scikit-learn
📂 Project Structure
project-folder/
│
├── phishing_detector.py
└── README.md
💻 Setup Instructions
First, make sure Python is installed on your system. You can check it by running:
python --version
Next, install the required libraries:
pip install pandas scikit-learn
After that, save the Python code file as:
phishing_detector.py
▶️ How to Run the Project
Open the terminal or command prompt and navigate to your project folder:
cd project-folder
Then run the program:
python phishing_detector.py
🧪 How to Use
After running the program, it will ask you to enter a URL
Enter any website link you want to check
The system will analyze it and display whether it is safe or phishing
To exit the program, type:
exit
📌 Example Output
Enter URL: https://www.youtube.com⁠�
Checking URL...
Trusted Website (Safe URL)
Enter URL: http://free-money.xyz⁠�
Checking URL...
Warning: This URL is likely a phishing attempt. Avoid entering sensitive information.
⚠️ Limitations
Dataset used is small and manually created
Model accuracy is limited
Only basic URL features are analyzed
Cannot detect advanced phishing attacks
🚀 Future Improvements
Use a larger real-world dataset
Apply advanced machine learning models
Add more detection features
Create a web-based version
Improve prediction accuracy
📖 Notes
This project is created for learning purposes to understand how phishing detection works using basic machine learning and Python programming concepts like functions, loops, and conditions.

 ***Phishing URL Detection***

**About This Project**
This project is all about detecting phishing websites using machine learning. Basically, you enter a URL, and it tells you if it’s safe or potentially harmful. I built it to help people avoid fake websites and online scams. It includes a trained model, some Python scripts, and a simple web interface, so anyone can try it out.
**Features**
- Check if a URL is safe or a phishing attempt.
- Easy web interface to input URLs and get results instantly.
- Python scripts for training and feature extraction.
- Can run on your computer using just Python — no fancy setup needed.
**How The Project Is Organized**
The project has the following structure:
- README.md – This file
-  Phishing URL Detection.ipynb – Notebook showing data analysis and model training
- app.py – Main Python script to run the detection app
- feature.py – Code to extract features from URLs
- phishing.csv – Dataset used for training/testing
- requirements.txt – Python packages needed
- templates/ – HTML files for the web app
- static/ – CSS & JS files for the web app
- Procfile – Deployment file (for Heroku, optional)
**What You Need**
- Python 3.8 or higher
- pip (Python package manager)
**How To Run It**
1. Clone the repository
Open a terminal and run:
git clone https://github.com/ArchiPatel07/Phishing-URL-Detection
cd Phishing-URL-Detection
2. Install the dependencies
pip install -r requirements.txt
3. Run the application
python app.py
4. Open the web interface
Go to http://127.0.0.1:5000/ in your browser. Enter a URL and click Check URL. The app will display whether the URL is Safe or Phishing.
**Example**
- Input: http://example.com/login → Output: Safe
- Input: http://secure-bank-login.com → Output: Phishing
**Project Report**
A detailed project report is included as Project Report.docx, which explains:
- What the project does and why it’s useful
- The dataset and features used
- How the model was trained and tested
- Results and conclusions
**Notes**
Make sure all dependencies are installed before running.
The project can be fully run from the command line — no extra GUI needed.
The dataset is included in the repo, so everything you need is already here.

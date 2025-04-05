# Morphle Labs Assignment - Aryaman Jain

**Author:** Aryaman Jain  
**Date:** 5th April 2025  

## 📌 Description

This is a simple web application built using **Flask** that replicates the functionality of the `top` command in Linux.  
It displays system information like:

- CPU usage
- Memory usage
- Active processes
- Load average
- Running time

The app dynamically fetches and displays the `top` command output along with the current user and timestamp.

---

## 🔧 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/Misprect/Assignment-morphlelabs.git
cd Assignment-morphlelabs
pip install -r requirements.txt
OR manually
pip install Flask pytz
Run the flask Application
python app.py
OPen my browser
http://localhost:5000/htop

Assignment-morphlelabs/
│
├── app.py                # Main Flask app
├── templates/
│   └── htop.html         # HTML template rendering output
├── requirements.txt      # Python dependencies
├── Screenshot ![Screenshot 2025-04-05 155812](https://github.com/user-attachments/assets/be892c4c-93d6-4c8e-815c-39e3f2611a0a)
 # Screenshot image
└── README.md             # Project documentation


✅ Technologies Used
Python

Flask

pytz (for timezone handling)

HTML (Jinja2 templating)

ryaman Jain
Feel free to connect or reach out if you have any feedback or suggestions!

---

### 📌 Also add this `requirements.txt` file to your repo:

```txt
Flask
pytz

# Smart Job Application Tracker

A Python automation tool to track internship/job applications with automatic email reminders.

## Features
- Track all job applications in one place  
- Automatic email reminder after 7 days of no response
- Data saved in Excel for permanent storage
- Built with OOPs principles — 3 classes, clean architecture
- Secure credential management using .env file  

## Tech Stack
- Python 
- OOPs (Encapsulation, Abstraction)
- openpyxl — Excel read/write
- smtplib — Email automation 
- python-dotenv — Secure credentials

## How to Run

1. Clone the repo
   git clone https://github.com/prachichauhan006/job-tracker

2. Install dependencies
   pip install openpyxl python-dotenv

3. Create .env file
   EMAIL=your_email@gmail.com
   PASSWORD=your_app_password

4. Run
   python job_tracker.py

## Project Structure
job-tracker/
├── job_tracker.py   
├── job_applications.xlsx        
├── .env             
├── .gitignore       
└── README.md        

## Author
Prachi Chauhan — B.Tech CSE '27 | AKTU
GitHub: prachichauhan006

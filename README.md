🕵️‍♂️ KIRA Screenshot Stealer

A sleek, beginner-friendly Linux tool to take screenshots — built with love for cybersecurity students by Naveen.

    ⚠️ For educational use only. Do not use this tool for illegal purposes.

🚀 Features

    ✨ Stylish terminal interaction

    💻 Runs on Linux (Kali, Ubuntu, ParrotOS etc.)

    📸 Auto-captures screenshot

    📬 Asks for user's Gmail (used for sending, feature coming soon!)

    📦 Auto installs dependencies

    🧠 Beginner-friendly

🛠️ Installation Guide (for Linux)

Follow the steps below to install and run Kira Screenshot Stealer:

🐍 1. Install Python 3 (if not installed)


sudo apt update

sudo apt install python3-pip -y

🔗 2. Clone the Repository

git clone https://github.com/Naveenkira/kira-screenshot-stealer.git

cd kira-screenshot-stealer


📦 3. Create Virtual Environment (optional but recommended)


python3 -m venv venv

source venv/bin/activate

🚀 4. Run Kira


python3 kira.py

It will:

    Install pyautogui automatically

    Guide you step by step in terminal

    Ask for your Gmail (optional)

    Take screenshot and save in the same folder

📷 Output

Your screenshot will be saved as:

screenshot_YYYYMMDD_HHMMSS.png

❓ FAQ

Q: Where does the screenshot go?
🅰️ It gets saved in the current folder.

Q: Is my Gmail used?
🅰️ Kira just asks for your Gmail now — it doesn’t send emails yet.

Q: It says Can't connect to display
🅰️ Run this inside a desktop Linux environment (not in headless terminal or SSH). GUI is required.
👨‍💻 Developed By

Naveen, cybersecurity enthusiast
GitHub: @Naveenkira
⚠️ Legal Disclaimer

This tool is for educational and ethical testing purposes only. The author is not responsible for any misuse.

# DailyPayment150526
A secure, modern desktop revenue tracking dashboard developed by 3D space. Built with Python and SQLite, it features real-time financial filtering, milestone tracking, and automated PDF/Excel reporting.

* Python Virtual Environment
venv/
env/

* PyInstaller Build Folders
build/
dist/
*.spec

* Database (Keep your business data private!)
*.db

* Python Cache
__pycache__/
*.pyc

* OS Files
.DS_Store
Thumbs.db

# SET UP GUIDE
* pyinstaller --noconsole --onefile --icon="icon.ico" --add-data "logo.png;." --add-data "icon.ico;." app.py
* pyinstaller --noconsole --onefile app.py

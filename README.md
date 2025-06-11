1 .Clone/Fork the git repo and create a virtual environment
Windows

git clone https://github.com/Dev-Elie/Flask-Docker-App.git
cd Flask-Docker-App
py -3 -m venv venv
macOS/Linux

git clone https://github.com/Dev-Elie/Flask-Docker-App.git
cd Flask-Docker-App
python3 -m venv venv
2 .Activate the environment
Windows

venv\Scripts\activate

macOS/Linux

. venv/bin/activate or source venv/bin/activate

3 .Install the requirements
Applies for windows/macOS/Linux

pip install -r requirements.txt
5. Run the application
python app.py

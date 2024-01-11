1. Setting up Code for Deployment
1.1. Create a new directory with the name attendance_system_app.
  $ mkdir attendance_system_app
1.2. Navigate to the folder
  $ cd attendance_system_app
1.3. Lets test the application developed in the previous lesson. First Create a virtual environment.
~/attendance_system_app $ python -m venv virtualenv
1.4. Activate the virtual environment
For Windows (Git Bash)
~/attendance_system_app $ source virtualenv/Scripts/activate
For Windows (Command Prompt or PowerShell),

~/attendance_system_app $ virtualenv\Scripts\activate
For Linux/Mac
~/attendance_system_app $ source virtualenv/bin/activate
1.5. Create another directory named app
  (virtualenv) ~/attendance_system_app $ mkdir app
1.6. Copy and paste the complete application code into the app directory.
1.7. Install required packages from requirements.txt in the app folder.
  (virtualenv) ~/attendance_system_app $ cd app
  (virtualenv) ~/attendance_system_app/app $ pip install -r requirements.txt
1.8. Run the application
  (virtualenv) ~/attendance_system_app/app $ streamlit run Home.py

## GameManage
A web app to collect your games in one place, and to search for new games.  




## Install Python 3.9  
We have used Python 3.9 for this project. Please ensure you have Python 3.9 or above installed in your system.  

Refer to https://www.python.org/downloads/ for downloading the latest version for your system.  

Linux:  
You may follow this page https://docs.python-guide.org/starting/install3/linux/ for guidance on installing Python 3.9 in a Linux system.  

macOS:  
You may follow this page https://python.tutorials24x7.com/blog/how-to-install-python-3-9-on-mac for guidance on installing Python 3.9 in a macOS system.  

Windows:  
You may follow this page https://www.ics.uci.edu/~pattis/common/handouts/pythoneclipsejava/python.html for guidance on installing Python 3.9 in a Windows system.  




## Install Flask  
1. Create environment  

Linux/macOS:  
python3 -m venv venv  

Windows:  
py -3 -m venv venv  

2. Activate the environment  

Linux/macOS:  
. venv/bin/activate  

Windows:  
venv\Scripts\activate  

3. Install Flask  

pip install Flask  

For more details, visit this [link](https://flask.palletsprojects.com/en/2.0.x/installation/)  

4. Install other dependencies  

pip install -r requirements.txt  

If you are contributing to this project, please ensure to update the requirements.txt file for other developers or users using the following command:  

pip freeze > requirements.txt




## Run Flask App  

Bash:  
export FLASK_APP=app  
flask run  

Powershell:  
$env:FLASK_APP = "app"
flask run  

For more details on running Flask applications, visit this [link](https://flask.palletsprojects.com/en/2.0.x/quickstart/)  

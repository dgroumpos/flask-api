# flask-api
***************************************
An example rest api project with Flask
***************************************

        SETUP INSTRUCTIONS
        __________________
1. Create a new project in github and clone it
2. Create virtual environment inside project folder:
    - Open the terminal
    - In the root project directory type python3 -m venv name-of-your-env (default is usually "venv")
    - Activate the virtual environment by typing source venv/bin/activate
    - Type pip install flask and press enter
3. Create requirements file - type "pip freeze > requirements.txt"
4. Create a docker-compose.yml file and include the necessary instructions
5. In the terminal, type docker-compose up -d
6. To terminate the docker containers:
    - Type docker ps to get the list of containers
    - Type docker stop -t 60 <container id>

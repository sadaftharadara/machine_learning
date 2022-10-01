Start Machine Learning project.
Software and account Requirement.

    [Github Account]
    [Heroku Account]
    [VS Code IDE]
    [GIT cli]
    [GIT Documentation]

Creating conda environment

conda create -p venv python==3.7 -y

conda activate venv/

OR

conda activate venv

pip install -r requirements.txt

To Add files to git

git add .

OR

git add <file_name>

    Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

git status

To check all version maintained by git

git log

To create version/commit all changes by git

git commit -m "message"

To send version/changes to github

git push origin main

To check remote url

git remote -v

To setup CI/CD pipeline in heroku we need 3 information

    HEROKU_EMAIL = sadaftharadara@gmail.com
    HEROKU_API_KEY = 151af59f-b6ea-46ba-83e1-d422a68b6e81
    HEROKU_APP_NAME = machine-learning-regression-ap

BUILD DOCKER IMAGE

    Note: Image name for docker must be lowercase

To list docker image

docker images

Run docker image

docker run -p 5000:5000 -e PORT=5000 4ddd71f86178



To check running container in docker

docker ps

Tos stop docker conatiner

docker stop <container_id>

python setup.py install

Install ipykernel

pip install ipykernel

Data Drift: When your datset stats gets change we call it as data drift
Write a function to get training file path from artifact dir

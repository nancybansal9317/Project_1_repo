A simple FastAPI app for DevOps hands-on demo.

```bash
#run locally
pip install -r requirements.txt
uvicorn main:app --reload


# git initialization 
git init
git add .  # add of the files to the git repo
git commit -m "Initial DevOps app commit" 
git remote add origin https://github.com/naaz-verma/worldwithweb-devops-app.git
git branch -M main # creating branch
git clone https://github.com/naaz-verma/worldwithweb-devops-app.git # for syncing every change


# Docker commands:
 docker build -t Project_1_repo .  # for building a container in the docker
 docker run -d -p 8000:8000 prject_1_repo # running and the coker image 
 docker ps #for listing  the running images.

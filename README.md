Git Repo Link - https://github.com/MAXBASH/sit737-2025-prac5p

Steps:

1.	“npm init” command in terminal, to create package.json file in project folder.
2.	“npm install express” command to install express.js framework.
3.	Created “server.js” file and written the code to display simple web page. 
4.	Ran “server.js” file by using “node server.js” command. 
5.	Pushed code into git repository.
6.	Created Docker file.
7.	Build docker image using “docker build -t sit737-prac5-app:latest .” command

8.	Created docker compose file
9.	Started docker compose environment by executing “docker compose up -d” command.
10.	Tested application
11.	Pushing docker image into registry using below commands.
docker login
docker tag sit737-prac5-app:latest manoz3896/sit737-prac5-app:latest
docker push manoz3896/sit737-prac5-app:latest



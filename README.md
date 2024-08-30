# Cloud-_-_Iaas-_basics--digital-_ocean_TWN

Exercises for Module "Cloud & IaaS - DigitalOcean"


Use repository: https://gitlab.com/twn-devops-bootcamp/latest/05-cloud/cloud-basics-exercises


You are asked to create a simple NodeJS app that lists all the projects each developer is working on. Everyone on your team wants to be able to see the list themselves and share with the project managers, so they ask you to make it available online, so everyone can access it.



EXERCISE 0: Clone Git Repository
For that you can use my provided git repository.

clone the git repository and
create your own project/git repo from it


EXERCISE 1: Package NodeJS App
To have just 1 file, you create an artifact from the Node App. So you do the following:

Package your Node app into a tar file (npm pack)


EXERCISE 2: Create a new server
Your company uses DigitalOcean as Infrastructure as a Service platform, instead of having on-premise servers. So you:

Create a new droplet server on DigitalOcean


EXERCISE 3: Prepare server to run Node App
Now you have a new fresh server nothing installed on it. Because you want to run a NodeJS application you need to install Node and npm on it:

Install nodejs & npm on it


EXERCISE 4: Copy App
Having everything prepared for the application, you finally:

Copy your simple Nodejs app to the droplet


EXERCISE 5: Run Node App
Start the node application in detached mode (npm install and node server.js commands)


EXERCISE 6: Access from browser - configure firewall
You see that the application is not accessible through the browser, because all ports are closed on the server. So you:

Open the correct port on Droplet
and access the UI from browser

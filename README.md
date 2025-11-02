q14 : # Set your global username and email
git config --global user.name "ATHARVA SHENDE"
git config --global user.email "atharva@example.com"

# Verify configuration
git config --list

# Create a new folder and navigate into it
mkdir g9devops
cd g9devops

# Initialize a new Git repository
git init

# Create a new file
echo "HELLO FROM GIT" > readme.txt

# Check the current status of the repository
git status

# Add all files to staging area
git add readme.txt

# Commit the changes with a message
git commit -m "Initial commit - added readme file"

# Add a remote repository (replace with your actual GitHub repo URL)
git remote add origin https://github.com/username/g9devops.git

# Push changes to remote repository
git push -u origin master

# Clone an existing repository (example)
git clone https://github.com/username/g9devops.git

# Pull latest changes from remote repository
git pull origin master



q15 : # Step 1: Create folder and enter it
mkdir myrepo
cd myrepo

# Step 2: Initialize Git repository
git init

# Step 3: Create a file
echo "This is my first Git file" > index.txt

# Step 4: Add file to staging
git add index.txt

# Step 5: Commit with a meaningful message
git commit -m "Added index.txt as initial file"

# Step 6: Connect to GitHub repository (replace URL)
git remote add origin https://github.com/username/myrepo.git

# Step 7: Push to remote repository
git push -u origin master


for pulling : 
git clone https://github.com/ASHBORN-11/XIE.git   or u can do   cd ~/sup  git init   git remote add origin https://github.com/ASHBORN-11/for_pulling.git  n then from 69 
cd sup


git pull origin master
echo "HELLO MAU" >> readme.txt
git status
git add .
git commit -m "Updated readme with new content"
git push origin master




docker normal commands / 10.	Pull Ubuntu image in Docker and execute bash 

sudo docker --version               # Check Docker version
sudo docker status
sudo docker info 
sudo docker pull ubuntu             # Pull latest Ubuntu image
sudo docker images                  # List all images
sudo docker run -it ubuntu /bin/bash     # Run Ubuntu container in interactive mode
pwd                                 # Show current directory inside Ubuntu container
ls                                  # List files in the current directory
mkdir testfolder                    # Create a test folder
cd testfolder                       # Move into the folder
echo "Hello from Docker Ubuntu!" > hello.txt   # Create a text file
cat hello.txt                       # Display file content
exit                                # Exit from Ubuntu container
sudo docker ps -a                   # Show all containers (running + stopped)

sudo docker pull alpine
sudo docker rmi alpine


q17 : 
code for html 
<html>
<body>
  <h1>HELLO</h1>
</body>
</html>

steps for 17 : 
mkdir html
cd html
nano index.html
vim Dockerfile
press i 
from httpd
copy ./ /usr/local/apache2/htdocs/
press: esc+shift+:
wq
sudo docker build -t index .
sudo docker run -d -p 8080:80 index
curl http://localhost:8080
go in the instance --> security group --> edit inbound rules --> tcp and port 8080
chrome --> http://ip:8080




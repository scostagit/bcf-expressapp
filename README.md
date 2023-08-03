bfc





install express 
npm install -g express-generator
npm install

Installing ebCLI 
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install-advanced.html
voclabs:~ $ source ~/.local/bin
bash: source: /home/ec2-user/.local/bin: is a directory
voclabs:~ $ source ~/.profile
voclabs:~ $ eb --version
Modify Script for Export


GitHub
echo "# Blockchain" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:sheeney1776/Blockchain.git
git push -u origin main

Branches
https://www.howtogeek.com/714112/how-to-create-a-new-branch-in-github/
git checkout -b <yourbranchname> 
git push origin <yourbranchname>


git branch

$ git checkout <existing_branch>

$ git checkout -b <new_branch>

$ git branch


https://devconnected.com/how-to-switch-branch-on-git/

Creation of Key 
ssh-keygen -t rsa -b 4096 -C "joe@example.com"
ress Enter to accept the default file location.
Enter a secure passphrase.
Press Enter.
Enter this command to display the contents of your public key:
cat .ssh/id_rsa.pub
Copy the contents of your key to your clipboard (we will need it later).




Create an SSH Key 
Add Key to GH 
Setup in Terminal 
Perform 

Git Add .
Git Commit - Write msg
Git Push 





sudo yum -y update      # Install the latest system updates.
sudo yum -y install git # Install Git.
git --version           # Confirm Git was installed.



git config --global user.name "USER_NAME"
git config --global user.email EMAIL_ADDRESS









…or create a new repository on the command line

echo "# Test88" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:user/repo
git push -u origin main

…or push an existing repository from the command line

git remote add origin YOUR SSH Destination
git branch -M main
git push -u origin main

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.







https://www.inmotionhosting.com/support/server/ssh/how-to-add-ssh-keys-to-your-github-account/
https://kbroman.org/github_tutorial/pages/init.html
https://medium.com/sonabstudios/setting-up-github-on-aws-cloud9-with-ssh-2545c4f989ea




AWS Elastic Beanstalk

    This service can assume the LabRole IAM role.

    To create an application: choose Create Application, give it an application name,  choose a platform, then choose Configure more options. Scroll down to the Security panel and choose Edit. For Service role, choose LabRole. 
    If the environment is in the us-east-1 AWS Region, for EC2 key pair, choose vockey and for IAM instance profile, choose LabInstanceProfile. Choose Save, then choose Create app.




Lint 
https://medium.com/@krs.30018/how-to-fix-your-javascript-linting-errors-in-four-easy-steps-e21498671f5f
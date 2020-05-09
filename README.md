# git formation #

# git configuration
git config --global user.email "kikinfo06@yahoo.fr"
git config --global user.name "Arezki75"

# Create a new repository
git init
git remote add origin https://github.com/Arezki75/Formation.git
git push -u origin master

# Push an existing repository
git remote add origin https://github.com/Arezki75/Formation.git
git push -u origin master

# git commands
git clone https://github.com/Arezki75/Formation.git
git add test.txt
git commit -m "Ajout test.txt"
git push origin master
git pull origin master

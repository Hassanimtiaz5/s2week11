echo "Going to Setup Repo"
git init
git branch -m develop
mkdir ./src ./styles ./assets ./bin ./node_modules
touch ./.gitignore ./src/index.html ./styles/index.css
git config --local user.name "Hassan Imtiaz"
git config --local user.email "l1s22bsse0032@ucp.edu.pk"
git config --local core.editor notepad 
git remote add origin https://github.com/Hassanimtiaz5/s2week11.git 
echo "!! Repository completed "
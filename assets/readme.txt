Hi
You can upload all the assets to this folder please make sure you dont directly push to main but make your own branch push there and create a pull request

Here are commands that might help

git checkout -b <branchname> // For first time branch creation
git checkout <branchname> // If you have made the branch before
git add <files> // add your assets
git commit -m "<your commit message>" //Put a meaningful commit message
git push -u origin <branchname> // Push to your branch
then create a pull req (main <- <your branch>)

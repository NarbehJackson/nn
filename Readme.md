Github-Action-Container 

Open terminal and Clone :

    git clone https://github.com/peteryerofski901/gh-actions-trivy.git

 Change the directory

     cd gh-actions-trivy

Check the URL of remote repo

    git remote -v 
    
Copy the URL of the newly created repo

    https://github.com/<your-github-username>/gh-actions-nodejsscan

change the origin to newly created repo

    git remote set-url origin https://github.com/<your-github-username>/gh-actions-nodejsscan.git

Open app.js in any of the code editor and add a comment
//added new repo and github actions

Commit the code to the repo

    git add -A
    git commit -m "added new codebase +Actions"

Push the code to the origin master

    git push -u origin master

On the browser click on Actions on the created repo

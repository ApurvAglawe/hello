Git

--> make sure you have git installed in your machine
--> go to github.com/new and create a new repository
--> give name and/or optional parameters and create
--> copy the http link of the repo
--> go to vs code terminal and enter command: [git clone https://....]
--> create a new file in the repo and save the file hello.html
--> First for a new change the changes are ony present in our local repo.
    these are the uncommited changes which we need to add to the commit in order to push those changes to the github.
    This Adding is done using [git add {filename}]
--> After adding either one or multiple files, the changes are still present in our local and are uncommited, we then need to run an additional command to commit.
--> commiting is done using [git commit -m{merge} "{comments}"]
--> this will merge the changes to github. go back to the web page and refresh to see your changes.
--> [git status] tells you what are all the pending changes
--> You can combine the git add step and the git commit step
--> [git commit -am "{comments}"] here -am stands for all the files that have been changed
--> you can also make changes form the webpage and save it, like someone else has pushed the changes to this repo.
--> use [git pull] to merge the changes
--> but what if we run into a conflict, someone else is changing a line which I am also working on at the same time
-->


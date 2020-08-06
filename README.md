# GithubTutorial
Basic Initialising commands and functionalities

Git Repository Command:
//If you are joining an ongoing project and you are new to the project use clone Command
$-  git clone <repourl>//1

//If you are starting a very new project use init to create a new repo
$-  git init//1

Git Repository New Branch Creation:

$-  git branch  //check the exsisting branch
$-  git checkout <branchname>  //select the new branch

//Add origin for proper connectivity between local and central repo.
// We call remote repo as origin. this is for sync purpose
$-  git remote add origin "https://github.com/PreDestin/GithubTutorial.git"//2

//Do pull to fetch files from central to local repo
&-  git pull origin master//3

//There is an intermediate between the workspace and the local repo
//where the changes you make to the local repo by commit command are indexed.
//And to add the untracked files to the index use add cmd.
$-  git add <filename>//4(b)
$-  git add -A//To add multiple files to the index at once.4(c)

//To see list of files in the index use status
$-  git status//4(a)

//after all the changes are made commit to local repo
$-  git commit -m "Commit message for others to understand"//5(a)
$-  git commit -a -m "Commit changes"//To commit multiple files at once.5(b)

//To see how git stores all the commits use log command
$-  git log

$-  git fetch
//After making all the necessary changes do push to the central repo.
//Don't make frequent changes as it may affect other contributors works
$-  git push

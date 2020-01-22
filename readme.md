# Master Git and Github #
Course link: <https://www.udemy.com/course/master-git-and-github-fastest-way-ever/l>


## Software Development Life Circle (SDLC) ##
* Planning
* Defining
* Designing
* Building
* Testing
* Deployment

## SDLC Methodologies ##
* Waterfall Model
* Agile Model
* Iterative Model
* Spiral Model
* V-Model
* Big Bang Model

## Source Code Management (SCM also VCS) ##
(VCS: Version Control System)
- Are software systems
- Records all changes for a set of files over time
- Allows you to share those changes
- Provide merging and tracking of recorded changes

`Why use SCM?`

    When working as a development team, SCM allow us:
        * To collaborate efficiently on a single codebase
        * Help resolve code conflicts
        * Makes it easy to share contents
        * Keep track of every changes: SCM as a Single Source of Truth
        * Provides a complete modification history

`Styles of SCM?`
- Local
- Centralized
- Distributed

## Cloud-based SCM ##

* GitHub
* Bitbucket by Atlassian
* Amazon CodeCommit
* Visual Studio Online by Microsoft
* SourceForge

## GitLab ##

- Using an open-source license, developed by GitLab Inc.
- A web-based Dev-Ops lifecycle tool 
- Provides a Git-repository manager
- Provides Wiki
- Issue tracking
- CI/CD pipeline features

## Installation Git by commands (on Linux) ##

    sudo apt update

    sudo apt install git

    git config --global user.name <username>
    git config --global user.email <email@gmail.com>

    git --version

## Git commands (using Linux for demo) ##

    git config --global user.name <username>
    git config --global user.email <email@gmail.com>

    git init <repoName>

    git clone <repoLink.git>

    git add .    //add files which were changed to staging area

    git push     //push all files in staging area to remote repository

    git fetch    //will not merge to current working copy, just create new branch name FETCH_HEAD

    git pull     //git pull = git fetch + git merge

    git status

    git diff

    git reset <fileName>

    git rm

    git log

    git branch    //show all local branches
    git branch -a  

    git checkout <branchNameToSwitch>  //switch from one branch to another 

    git merge

    git remote

# git_assignment_HeroVired
Question Number 1 : You are part of a development team working on a Python application called "CalculatorPlus." The application provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. Your task is to implement a new feature that adds support for calculating the square root of a number.
steps followed : 1) created a repository : git_assignment_HeroVired
                 2) Then created a branch : dev 
                 3) Then added the base code mentioned in the question .
                 4) Then merged the dev branch with main branch to make a release of version 1 of the ‘calculator plus app’. by using a pull request
                 5) Then added one of batch mate as the collaborators
                 6) Created a new branch feature/sqrt for implementing a new feature , then added the 'sqrt' code mentioned in the question to the branch 
                 7) Them implemented a critical bug in dev branch
                 8) Then sent the code reivew request to my batch for review and approval
                 9) Once the pull request was approved , then merged 'feature/sqrt' branch into 'dev' branch 
                10) Then after testing the code in 'dev' branch , merged it with 'main' branch by creating a pull request and created 'version 2' release
Question No.2 : For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.
steps followed : 1) Installed git lfs using command : 'git lfs install'
                 2) Cloned the repository git_assignment_HeroVired using :  'git clone https://github.com/YogeshAtigre/git_assignment_HeroVired.git'
                 3) Created a New Branch for LFS using : 'git checkout -b lfs'
                 4) Tracked the Large Files Using Git LFS : 'git lfs track "*.extension_of_the_file_to_be_tracked"
                 5) Copied the file to be pushed using cp command 
                 6) Then added , commited and pushed the file into the lfs branch of the repository 
                 7) Commands used : git add .
                                    git commit -m "Comment to be given" 
                                    git push origin lfs 
                8) Then Cloned the repository on the another machine and switched into the 'lfs' branch and checked the file downloaded file 
Question No.3 : In this same GitHub repository, create a new branch ‘geometry-calculator’, we'll work on a simple Python program that calculates the area of a circle and the area of a rectangle. We'll use Git stash to switch between working on multiple features (calculating circle area and calculating rectangle area) without committing
steps followed : 1) Created a new branch ‘geometry-calculator'
                 2) Then added the base code 
                 3) Created a New Branch for Circle Area Feature using : 'git checkout -b feature/circle-area'
                 4) Then added the Circle Area Feature code mentioned in the code.
                 5) Then stashed the changes before committing using : git stash
                 6) The checked the working tree is clean or not using : git status
                 7) Created a branch for the rectangle area feature using : 'git checkout -b feature/rectangle-area'
                 8) Then added the  rectangle area feature code mentioned in the code.
                 9) Then stashed the changes before committing using : git stash
                 10) The checked the working tree is clean or not using : git status
                 11) Then switched back to the feature/circle-area branch using : 'git checkout feature/circle-area'
                 12) retrieved the stashed changes using : 'git stash pop'
                 13) Completed the implementation for the circle area and then added , commited , pushed the changes using following commands :
                      git add .
                      git commit -m "Comment to be given"
                      git push origin feature/circle-area
                14) Then switched to the feature/rectangle-area branch using : 'git checkout feature/rectangle-area'
                15) retrieved the stashed changes using : 'git stash pop'
                16) Completed the implementation for the rectangle area and then added , commited , pushed the changes using following commands :
                      git add .
                      git commit -m "Comment to be given"
                      git push origin feature/rectangle-area
                17) Then created a pull request for merging of both branches into the 'dev' branch and sent a code reviewal and pull request approval to my batch mate 
                18) After reviewing and receiving approval, merge the pull requests into the main branch.

# CPlusPlus-1
This repository contains some material I've created to teach courses on C++ and the Standard Template Library (STL).  Please see http://www.dre.vanderbilt.edu/~schmidt/cs251 for more information on these topics, including video presentations and slides.

https://www.youtube.com/playlist?list=PLZ9NgFYEMxp4pM7cZTe48udxbI1fR0zbM

https://gitlab.com/kshdes/software_design_usingcplusplus

https://github.com/douglascraigschmidt/CS251/wiki/Installing-Software



# Git global setup

git config --global user.name "kshdes"

git config --global user.email "ksh.desh@outlook.com"

# Create a new repository

git clone https://gitlab.com/kshdes/software_design_usingcplusplus.git

cd software_design_usingcplusplus

touch README.md

git add README.md

git commit -m "add README"

git push -u origin master


# Push an existing folder

cd existing_folder

git init

git remote add origin https://gitlab.com/kshdes/software_design_usingcplusplus.git

git add .

git commit -m "Initial commit"

git push -u origin master


# Push an existing Git repository

cd existing_repo

git remote rename origin old-origin

git remote add origin https://gitlab.com/kshdes/software_design_usingcplusplus.git

git push -u origin --all

git push -u origin --tags



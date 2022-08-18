# CMPG-323-Overview-33637008
## Project Structure for the semester
There will be one github Kanban project that will be used to keep track of the work of all 5 projects that are due for this semester, as well as the Portfolio of evidence. Each project will however have their own Repository.

### Diagram to illustrate project linkage with repos
![Blank diagram (1)](https://user-images.githubusercontent.com/56234654/185401219-92e0ceb9-908e-4770-bae1-20ede6bab909.png)

## Branching Strategy
I will be employing a very basic branching strategy. It will consist of a Main branch, and any new features that get added will be branched of from main, as soon as the feature is done it will be merged back into Main. Any bugfixes or hotfixes will also require a branch to be created from main, and when done it can be branched back into main. I prefer this above creating a main and development branch as it keeps things more simple and organised.

### Below is an image to illustrate the 2 different branching strategies that we will employ on our projects
![branchingStrategy](https://user-images.githubusercontent.com/56234654/185398377-2df52459-1fec-4119-a90c-52d7ffbec85d.png)

## Usage of .gitignore files
Git ignore files will be used in some of the projects that will be needing them. They are used to not upload some files to git, these files include secure information that you want not to be made publicly available, or files that can be built on the production server such as javascript dependencies.
## Repository Strategy
Each project will have it's own repository. That means there will be a total of 5 repositories, including this one. Each repository will link back to the main Kanban Project that we created for Project 1
## Storage of Credentials
The secret credentials will be stored locally for now, and if it is needed it can be requested. In the future we will look into storing them in either Azure ID or using an encryption program to store the files, and then share a seed file which can be used to decrypt the files.

#### PLEASE NOTE
Sources file is in the repo

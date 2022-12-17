# my-project
# download repository from github
# open code -> open terminal (bash)
# cd C:/Users/User/Downloads/Mate/myProjects
# git clone https://github.com/tania-kuzmenko/my-project.git
# open folder my-project
# git status
# git checkout -b develop
# create index.html
# git status
# git add index.html
# git commit -m 'index.html is created'
# check server git remote
# git remote show origin (to delete server: git remote remove origin)
# to add back git remote add origin https://github.com/tania-kuzmenko/my-project.git
# add branch develop to github: git push origin develop
# get changes ade on github: git pull origin develop
# SSH key: 
# 1) check existing key $ ls -al ~/.ssh~ 
# 2) generate: $  ssh-keygen -t ed25519 -C "tanch.sergeevich@gmail.com"
# 3) auto launch SSH agent: $ eval $(ssh-agent -s)
# 4) add key to SSH-aget: $ ssh-add ~/.ssh/id_ed25519
# 5) run key to git-account: $ clip < ~/.ssh/id_ed25519.pub
# key is in the buffer -> button New SSH key -> give name cntrl+V -> save
# download repository using SSH link:
# 1) git bush here in the folder project 
# 2) clone <SSH link>
# 3) say yes for using SSH key 
# 4) open VS code
# 5) go to develop branch
* git status
* git add . // git add file_name
* git commit -m "message" //  git commit -am "message while adding modified files without non-created"
* git remote add origin https://repo_link.git // (origin = remote url reference / alias)
* git branch -M new_branch_name // to rename current branch
* git checkout branch_name_to_navigate // only switch
* git checkout -b branch_name_to_navigate_and_create // switch + create
* git switch branch_name_to_navigate // for switching between branches only
* git reset // undo for (git add .) 
* git reset file_name// undo for (git add file_name) 
* git reset HEAD // undo last commit 
* git push -u origin main // -u = upstream, origin=alias/remote reference to push, main=branch_name
* git pull origin main // will pull main_branch from origin_remote to currently navigated branch
* git fetch origin // will fetch all branches to local
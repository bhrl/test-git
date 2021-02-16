

# test-git

…or create a new repository on the command line
echo "# test-git" >> README.md
1. git init
2. git add README.md
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/bhrl/test-git.git
6. git push -u origin main

…or push an existing repository from the command line
1. git remote add origin https://github.com/bhrl/test-git.git
2. git branch -M main
3. git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

..edit isi dari branch baru 
	
1. git checkout -b new_branch

2. git status 

3. git add new_file.txt

4. git status 

5. git commit -m "tambah new_file.txt coi"

6. git push -u origin new_branch

7. Once you push the changes to your repo, the Compare & pull request button will appear in GitHub

8. Click it and you'll be taken to this screen:

9. Open a pull request by clicking the Create pull request button. This allows the repo's maintainers to review your contribution. From here, they can merge it if it is good, or they may ask you to make some changes

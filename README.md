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


A. Membuat Brach dengan git client (bash)
	
	-  git checkout -b new_branch

B. saya coba menambah file  (dibawah ini command  linux  buat file baru namanya tes 

	- echo “isi dari file test ” > test_new_file 
	- cat test_new_file ( ini cek isi file test ) 

C. Melihat perubahan dari repository kita ( client ) 
	
	- git status 



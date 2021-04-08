#Read me
Info on this course

To show a listing of files

	ls

To show files in git folder

	ls -la will show files in git folder
        


git push origion master to say exactly were to put the files

To find out difference of the file on PC and file in Git 

	git diff file.name       git diff README.md

To see the history of files uploaded

	git log

If you happen to mess a file up you can use the following command which will reverse the local file back to the last commit. 

	git checkout filename.xxx


#Nice commands

This command can be added to the git.config file

git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'


git lg. It's like git log but wayyyyyyyy better


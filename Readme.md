To add this repository to an existing git/VSCode project, delete your .vscode folder and run this
Git command: 

	git submodule add https://github.com/BCZGnth/XC8_VSCode_Tasks.git .vscode/

This will add the repo as a submodule to your project. 
(Meaning Github Desktop will not be able to use it in any meaningful way, 
and may break the rest of your project in trying to reconcile the submodule)

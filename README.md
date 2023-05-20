## Bundle 4
# Exercise 1
```bash
PS C:\Users\student\Downloads\git_copy> echo "# git-copy" >> README.md
PS C:\Users\student\Downloads\git_copy> git init
Initialized empty Git repository in C:/Users/student/Downloads/git_copy/.git/
PS C:\Users\student\Downloads\git_copy> git add README.md
PS C:\Users\student\Downloads\git_copy> git commit -m "initial commit"
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
PS C:\Users\student\Downloads\git_copy> git remote add origin https://github.com/AL2002MI08/git-copy.git
PS C:\Users\student\Downloads\git_copy> git add --all 
PS C:\Users\student\Downloads\git_copy> git commit -m "created git copy repo"
[master c0eb82f] created git copy repo
 1 file changed, 11 insertions(+)
 create mode 100644 home.html
PS C:\Users\student\Downloads\git_copy> git pus origin main
git: 'pus' is not a git command. See 'git --help'.
The most similar commands are
        push
        pull
PS C:\Users\student\Downloads\git_copy> git push origin main 
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 595 bytes | 85.00 KiB/s, done.
To https://github.com/AL2002MI08/git-copy.git
PS C:\Users\student\Downloads\git_copy> git remote add git-copy https://github.com/AL2002MI08/git-copy.git 
PS C:\Users\student\Downloads\git_copy> git add --all
PS C:\Users\student\Downloads\git_copy> git commit -m "added homepage" 
[main 8e3fbbd] added homepage
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AL2002MI08/git-copy.git
PS C:\Users\student\Downloads\git_copy> git push git-copy main
Everything up-to-date
git-copy        https://github.com/AL2002MI08/git-copy.git (fetch)
git-copy        https://github.com/AL2002MI08/git-copy.git (push)
origin  https://github.com/AL2002MI08/git-copy.git (push)
PS C:\Users\student\Downloads\git_copy> git add .
PS C:\Users\student\Downloads\git_copy> git commit -m "new changes to home"
[main 73ad3a7] new changes to home
PS C:\Users\student\Downloads\git_copy> git push origin gym-git-exercise
error: src refspec gym-git-exercise does not match any
error: failed to push some refs to 'https://github.com/AL2002MI08/git-copy.git'
PS C:\Users\student\Downloads\git_copy> git push origin gym-git-exercise-solutions
error: src refspec gym-git-exercise-solutions does not match any
error: failed to push some refs to 'https://github.com/AL2002MI08/git-copy.git'
PS C:\Users\student\Downloads\git_copy> git push origin gym-git-exercise-solutions
error: failed to push some refs to 'https://github.com/AL2002MI08/git-copy.git'
PS C:\Users\student\Downloads\git_copy> git push origin Gym-Git-Exercise-Solutions
error: src refspec Gym-Git-Exercise-Solutions does not match any
error: failed to push some refs to 'https://github.com/AL2002MI08/git-copy.git'
PS C:\Users\student\Downloads\git_copy> git remote -v
git-copy        https://github.com/AL2002MI08/git-copy.git (fetch)
git-copy        https://github.com/AL2002MI08/git-copy.git (push)
PS C:\Users\student\Downloads\git_copy> rm -fr origin
Remove-Item : A parameter cannot be found that matches parameter name 'fr'.
+    ~~~
    + CategoryInfo          : InvalidArgument: (:) [Remove-Item], ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.PowerShell.Commands.RemoveItemCommand
 
rm : Cannot find path 'C:\Users\student\Downloads\git_copy\origin' because it does not exist.
At line:1 char:1
+ rm  origin
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\studen...git_copy\origin:String) [Remove-Item], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.RemoveItemCommand
 
PS C:\Users\student\Downloads\git_copy> git remote rm origin
PS C:\Users\student\Downloads\git_copy> git remote -v
git-copy        https://github.com/AL2002MI08/git-copy.git (push)
PS C:\Users\student\Downloads\git_copy> git remote add origin https://github.com/AL2002MI08/Gym-Git-Exercise-Solutions.git
PS C:\Users\student\Downloads\git_copy> git remote -v
git-copy        https://github.com/AL2002MI08/git-copy.git (fetch)
git-copy        https://github.com/AL2002MI08/git-copy.git (push)
origin  https://github.com/AL2002MI08/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/AL2002MI08/Gym-Git-Exercise-Solutions.git (push)
PS C:\Users\student\Downloads\git_copy> git push git-copy
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 343 bytes | 114.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AL2002MI08/git-copy.git
   8e3fbbd..73ad3a7  main -> main
PS C:\Users\student\Downloads\git_copy> git push -f origin main
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (12/12), 1.15 KiB | 195.00 KiB/s, done.
Total 12 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/AL2002MI08/Gym-Git-Exercise-Solutions.git
 + 871d475...73ad3a7 main -> main (forced update)
```

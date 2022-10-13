# Premiers pas



## Premier repository sur GITHUB

Voici mon tout premier repository sur GITHUB, je vais en profiter pour y glisser mes quelques **antisèches GIT BASH**

Voilà ce que j'ai appris avec le cours OPENCLASSROOM ("Gérez du code avec Git et GITHUB" = https://openclassrooms.com/fr/courses/7162856-gerez-du-code-avec-git-et-github) et d'autres sources, à la fin du README
Faites pas les fourbes, un "dépôt" = "repository"


- Créer un repository (dépôt) sur GITHUB :
> $ echo "#test" >> README.md

> $ git init

> $ git add README.md

> $ git commit -m "[description du commit]"

> $ git branch -M main

Aller se connecter sur github, dans Your repositories (en haut à droite)

Créer un nouveau repository

Lui donner un joli nom (note : il peut être modifié plus tard mais attention, il faudra changer l'url de dépôt distant sur le GIT local)

Copier l'URL du dépôt distant

> $ git remote add origin [+coller l'URL du repository]

> $ git push  -u origin main 

Changer le nom du dépôt distant
(https://careerkarma.com/blog/git-change-remote/) 

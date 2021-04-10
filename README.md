# SI_2021_lab1_153205
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git init
get : The term 'get' is not recognized as the name of a cmdlet, function, script file, or        
operable program. Check the spelling of the name, or if a path was included, verify that the     
path is correct and try again.
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git remote add origin
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git remote add origin https://github.com/nenonnxy/SI_2021_lab1_153205.git
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git push
fatal: The current branch master has no upstream branch.      

    git push --set-upstream origin master
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nenonnxy/SI_2021_lab1_153205.git
 * [new branch]      master -> master
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git push --set-upstream origin master
Everything up-to-date
Branch 'master' set up to track remote branch 'master' from 'origin'.
[master fead207] Add numbers from 6-9
 1 file changed, 4 insertions(+)
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 283 bytes | 283.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/nenonnxy/SI_2021_lab1_153205.git
   500a07d..fead207  master -> master
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git log
PS C:\Users\Neno\Desktop\SI_2021_lab1_153205> git log
commit 5c8e3ca1af4e9ca37a64a7dc03a6f3281c737a05 (HEAD -> master, origin/master)
Author: nenonnxy <63436873+nenonnxy@users.noreply.github.com>
Date:   Sat Apr 10 16:00:02 2021 +0200

    Add some words

commit fead207bfa74a89c836bfe84bd1e393c6743bc96
Author: nenonnxy <63436873+nenonnxy@users.noreply.github.com>
Date:   Sat Apr 10 15:58:22 2021 +0200

    Add numbers from 6-9
:

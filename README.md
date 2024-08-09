# git_test_public

hier muss alles um den git geht

1.current branch main und master sind unterschied
git push origin main/master
git push:abgeben von local zu den remote
origin:defalt name fuer den remote Halle
main/master ist den default

2.Wenn man allein im gitbash mit dem Datei, der später noch im VScode bearbeitet werden, muss den folgende Schritte folgen:
8

If Existing Project Solution is planned to move on TSF in VS Code:

open Terminal and run following commands:

Initialize git in that folder (root Director)
git init

Add Git

git add .

Link your TSf/Git to that Project - {url} replace with your git address

git remote add origin {url}

Commit those Changes:

git commit -m "initial commit"

Push - I pushed code as version1 you can use any name for your branch

git push origin HEAD:Version1

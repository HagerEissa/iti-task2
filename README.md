$ mkdir iti-task
$ cd iti-task
$ git init
$ git add main.txt
$ git commit -m "initial commit"
$ git remote add origin https://github.com/HagerEissa/iti-task2.git
$ git branch -M main
$ git push -u origin main
$ git checkout -b dev
$ echo "this is dev file" > dev.txt
$ git add dev.txt
$ git commit -m "dev file added"
$ git push -u origin dev
$ git checkout main
$ git checkout -b test
$ echo "this is test file" > test.txt
$ git add test.txt
$ git commit -m "add test file"
$ git push -u origin test
$ git checkout main
$ git merge dev
$ git merge test
$ git push origin main
$ git tag -a v1.7 -m "release v1.7"
$ git push origin v1.7


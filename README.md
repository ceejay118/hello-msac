Cloning into 'hello-msac'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 702 bytes | 351.00 KiB/s, done.
From github.com:sc137/hello-msac
   fe14262..25eca1c  main       -> origin/main
Updating fe14262..25eca1c
Fast-forward
 README.md | 2 ++
 1 file changed, 2 insertions(+)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add ..." to update what will be committed)
  (use "git restore ..." to discard changes in working directory)
    modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
$ git add README.md 
$ git commit -m "Edited locally."
[main 1e466dc] Edited locally.
 1 file changed, 2 insertions(+)

 % git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:sc137/hello-msac.git
   25eca1c..1e466dc  main -> main

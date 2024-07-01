"# my-first-repo"
practicing on my own
added all the code for future refrence Microsoft Windows [Version 10.0.19045.4412]
(c) Microsoft Corporation. All rights reserved.

C:\Users\practica>dir
 Volume in drive C has no label.
 Volume Serial Number is BE33-5183

 Directory of C:\Users\practica

01/07/2024  16:03    <DIR>          .
01/07/2024  16:03    <DIR>          ..
01/07/2024  15:13               173 .gitconfig
01/07/2024  16:03                20 .lesshst
24/10/2023  09:36    <DIR>          3D Objects
24/10/2023  09:36    <DIR>          Contacts
01/07/2024  15:54    <DIR>          Desktop
09/05/2024  13:44    <DIR>          Documents
01/07/2024  15:57    <DIR>          Downloads
24/10/2023  09:36    <DIR>          Favorites
24/10/2023  09:36    <DIR>          Links
24/10/2023  09:36    <DIR>          Music
24/10/2023  09:37    <DIR>          OneDrive
07/05/2024  18:21    <DIR>          Pictures
24/10/2023  09:36    <DIR>          Saved Games
24/10/2023  09:37    <DIR>          Searches
07/03/2024  12:23    <DIR>          Videos
               2 File(s)            193 bytes
              15 Dir(s)  27,992,584,192 bytes free

C:\Users\practica>cd Desktop

C:\Users\practica\Desktop>cd my-first-repo

C:\Users\practica\Desktop\my-first-repo>echo "# my-first-repo" >> README.md

C:\Users\practica\Desktop\my-first-repo>git init
Initialized empty Git repository in C:/Users/practica/Desktop/my-first-repo/.git/

C:\Users\practica\Desktop\my-first-repo>git add README.md

C:\Users\practica\Desktop\my-first-repo>git commit -m "first commit"
[master (root-commit) 0fcdfb6] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\practica\Desktop\my-first-repo>git branch -M main

C:\Users\practica\Desktop\my-first-repo>git remote add origin https://github.com/Jomo10/my-first-repo.git

C:\Users\practica\Desktop\my-first-repo>git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 226 bytes | 226.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Jomo10/my-first-repo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

C:\Users\practica\Desktop\my-first-repo>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\practica\Desktop\my-first-repo>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\practica\Desktop\my-first-repo>git add README.md

C:\Users\practica\Desktop\my-first-repo>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


C:\Users\practica\Desktop\my-first-repo>git commit "adding zain to readme"
error: pathspec 'adding zain to readme' did not match any file(s) known to git

C:\Users\practica\Desktop\my-first-repo>git commit -m "adding zain to readme"
[main 3d4c6e7] adding zain to readme
 1 file changed, 1 insertion(+)

C:\Users\practica\Desktop\my-first-repo>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 266 bytes | 266.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Jomo10/my-first-repo.git
   0fcdfb6..3d4c6e7  main -> main

C:\Users\practica\Desktop\my-first-repo>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\practica\Desktop\my-first-repo>git diff
diff --git a/README.md b/README.md
index 4a45bcb..b2139ea 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1 @@
-"# my-first-repo"
-zain
+"# my-first-repo"

C:\Users\practica\Desktop\my-first-repo>git add README.md

C:\Users\practica\Desktop\my-first-repo>git commit -m "removing zain"
[main b4fed04] removing zain
 1 file changed, 1 insertion(+), 2 deletions(-)

C:\Users\practica\Desktop\my-first-repo>git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 256 bytes | 128.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Jomo10/my-first-repo.git
   3d4c6e7..b4fed04  main -> main

C:\Users\practica\Desktop\my-first-repo>git branch
* main

C:\Users\practica\Desktop\my-first-repo>git branch yusuf_dev

C:\Users\practica\Desktop\my-first-repo>git branch
* main
  yusuf_dev

C:\Users\practica\Desktop\my-first-repo>git checkout yusuf_dev
Switched to branch 'yusuf_dev'

C:\Users\practica\Desktop\my-first-repo>git branch
  main
* yusuf_dev

C:\Users\practica\Desktop\my-first-repo>git status
On branch yusuf_dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\practica\Desktop\my-first-repo>git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"

C:\Users\practica\Desktop\my-first-repo>git add README.md

C:\Users\practica\Desktop\my-first-repo>git status
On branch yusuf_dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


C:\Users\practica\Desktop\my-first-repo>git commit -m "added aaa message"
[yusuf_dev 44e0bd3] added aaa message
 1 file changed, 1 insertion(+)

C:\Users\practica\Desktop\my-first-repo>git push -u origin yusuf_dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 258 bytes | 258.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'yusuf_dev' on GitHub by visiting:
remote:      https://github.com/Jomo10/my-first-repo/pull/new/yusuf_dev
remote:
To https://github.com/Jomo10/my-first-repo.git
 * [new branch]      yusuf_dev -> yusuf_dev
branch 'yusuf_dev' set up to track 'origin/yusuf_dev'.

C:\Users\practica\Desktop\my-first-repo>git status
On branch yusuf_dev
Your branch is up to date with 'origin/yusuf_dev'.

nothing to commit, working tree clean

C:\Users\practica\Desktop\my-first-repo>git add README.md "2n practice"
fatal: pathspec '2n practice' did not match any files

C:\Users\practica\Desktop\my-first-repo>git add README.md

C:\Users\practica\Desktop\my-first-repo>git status
On branch yusuf_dev
Your branch is up to date with 'origin/yusuf_dev'.

nothing to commit, working tree clean

C:\Users\practica\Desktop\my-first-repo>git add README.md

C:\Users\practica\Desktop\my-first-repo>git status
On branch yusuf_dev
Your branch is up to date with 'origin/yusuf_dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


C:\Users\practica\Desktop\my-first-repo>git commit -m "2nd solo try"
[yusuf_dev edb8165] 2nd solo try
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\practica\Desktop\my-first-repo>git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 278 bytes | 278.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Jomo10/my-first-repo.git
   44e0bd3..edb8165  yusuf_dev -> yusuf_dev

C:\Users\practica\Desktop\my-first-repo>



User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou
$ git init
Initialized empty Git repository in C:/Users/User/Desktop/Folder nou/.git/

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ mkdir catalin

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ mkdir cretu

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ cd catalin

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ touch 1.txt 2.txt 3.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

nothing added to commit but untracked files present (use "git add" to track)

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ echo "10.03.2023">>1.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ cat 1.txt
10.03.2023

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ echo "martie">>2.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ echo "2023">>3.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/catalin (master)
$ cd ..

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ cd cretu

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/cretu (master)
$ touch pm.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/cretu (master)
$ nano pm.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/cretu (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../catalin/
        ./

nothing added to commit but untracked files present (use "git add" to track)

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou/cretu (master)
$ cd ..

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ git add .
warning: LF will be replaced by CRLF in catalin/1.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in catalin/2.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in catalin/3.txt.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in cretu/pm.txt.
The file will have its original line endings in your working directory

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   catalin/1.txt
        new file:   catalin/2.txt
        new file:   catalin/3.txt
        new file:   cretu/pm.txt


User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ git commit -m "Eu sunt catalin cretu din w-1942"
[master (root-commit) 9b3836a] Eu sunt catalin cretu din w-1942
 4 files changed, 4 insertions(+)
 create mode 100644 catalin/1.txt
 create mode 100644 catalin/2.txt
 create mode 100644 catalin/3.txt
 create mode 100644 cretu/pm.txt

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$ git status
On branch master
nothing to commit, working tree clean

User@LAB33_PC24 MINGW64 ~/Desktop/Folder nou (master)
$

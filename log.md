Last login: Sun Mar 21 21:17:56 2021 from pool-108-29-106-111.nycmny.fios.verizon.net
[kpatel@sol25 ~]$ echo "#Repo1" >>REAME.md
[kpatel@sol25 ~]$ git init
Reinitialized existing Git repository in /users1/st/kpatel/.git/
[kpatel@sol25 ~]$ git add README.md
fatal: pathspec 'README.md' did not match any files
[kpatel@sol25 ~]$ 
[kpatel@sol25 ~]$ git init
Reinitialized existing Git repository in /users1/st/kpatel/.git/
[kpatel@sol25 ~]$ cd kpatel
-bash: cd: kpatel: No such file or directory
[kpatel@sol25 ~]$ ^C
[kpatel@sol25 ~]$ cd  /users1/st/kpatel/.git/
[kpatel@sol25 .git]$ echo "Repo1" >> README.md
[kpatel@sol25 .git]$ 
[kpatel@sol25 .git]$ init
init: required argument missing.
[kpatel@sol25 .git]$ git init
Initialized empty Git repository in /users1/st/kpatel/.git/.git/
[kpatel@sol25 .git]$ git add Readme.md
fatal: pathspec 'Readme.md' did not match any files
[kpatel@sol25 .git]$ echo "#REPO1" >>README.md
[kpatel@sol25 .git]$ git init
Reinitialized existing Git repository in /users1/st/kpatel/.git/.git/
[kpatel@sol25 .git]$ git add README.md
[kpatel@sol25 .git]$ git commit -m "first commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'kpatel@sol25.(none)')
[kpatel@sol25 .git]$ git branch -M main
error: refname refs/heads/master not found
fatal: Branch rename failed
[kpatel@sol25 .git]$ ^C
[kpatel@sol25 .git]$ git config --global user.name "Your Name"
[kpatel@sol25 .git]$ git config --global user.name "Krunal Patel"
[kpatel@sol25 .git]$ git commit -m "first commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'kpatel@sol25.(none)')
[kpatel@sol25 .git]$ --global
bash: --global: command not found...
[kpatel@sol25 .git]$ git add README.md
[kpatel@sol25 .git]$ git commit -m "First commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'kpatel@sol25.(none)')
[kpatel@sol25 .git]$ git init -b main
error: unknown switch `b'
usage: git init [-q | --quiet] [--bare] [--template=<template-directory>] [--shared[=<permissions>]] [directory]

    --template <template-directory>
                          directory from which templates will be used
    --bare                create a bare repository
    --shared[=<permissions>]
                          specify that the git repository is to be shared amongst several users
    -q, --quiet           be quiet
    --separate-git-dir <gitdir>
                          separate git dir from working tree

[kpatel@sol25 .git]$ git init REPO1 main
usage: git init [-q | --quiet] [--bare] [--template=<template-directory>] [--shared[=<permissions>]] [directory]
[kpatel@sol25 .git]$ git add README.md 
[kpatel@sol25 .git]$ git commit -m "First commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'kpatel@sol25.(none)')
[kpatel@sol25 .git]$ git config --global user.email "you@example.com"
[kpatel@sol25 .git]$ git config --global user.email "krunalpatel5678@gmail.com"
[kpatel@sol25 .git]$ git commit -m "first commit"
[master (root-commit) 4d4a7f3] first commit
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
[kpatel@sol25 .git]$ git branch -M main
[kpatel@sol25 .git]$ git remote add origin https://github.com/krunalpatel5678/Repo1
[kpatel@sol25 .git]$ git push -u origin main


Username for 'https://github.com': Password for 'https://github.com': 
remote: Repository not found.
fatal: Authentication failed for 'https://github.com/krunalpatel5678/Repo1/'
[kpatel@sol25 .git]$ git push -u origin main
Username for 'https://github.com': krunalpatel5678
Password for 'https://krunalpatel5678@github.com': 
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/krunalpatel5678/Repo1/'
[kpatel@sol25 .git]$ git push -u origin main
Username for 'https://github.com': krunalpatel5678
Password for 'https://krunalpatel5678@github.com': 
To https://github.com/krunalpatel5678/Repo1
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/krunalpatel5678/Repo1'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first merge the remote changes (e.g.,
hint: 'git pull') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
[kpatel@sol25 .git]$ git pull
Username for 'https://github.com': krunalpatel5678
Password for 'https://krunalpatel5678@github.com': 
warning: no common commits
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/krunalpatel5678/Repo1
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

[kpatel@sol25 .git]$ echo "#Repo1" >> README>md
[kpatel@sol25 .git]$ git init
Reinitialized existing Git repository in /users1/st/kpatel/.git/.git/
[kpatel@sol25 .git]$ git add README.md
[kpatel@sol25 .git]$ git commit -m "first commit"
# On branch main
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#       HEAD
#       README
#       config
#       description
#       hooks/
#       index
#       info/
#       md
#       objects/
nothing added to commit but untracked files present (use "git add" to track)
[kpatel@sol25 .git]$ git branch -M main
[kpatel@sol25 .git]$ git remote add origin https://github.com/krunalpatel5678/Repo1
fatal: remote origin already exists.
[kpatel@sol25 .git]$ git push -u origin main
Username for 'https://github.com': krunalpatel5678
Password for 'https://krunalpatel5678@github.com': 
To https://github.com/krunalpatel5678/Repo1
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/krunalpatel5678/Repo1'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first merge the remote changes (e.g.,
hint: 'git pull') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
[kpatel@sol25 .git]$ git add Helloworld.java
fatal: pathspec 'Helloworld.java' did not match any files
[kpatel@sol25 .git]$ git add HelloWorld.java
fatal: pathspec 'HelloWorld.java' did not match any files
[kpatel@sol25 .git]$ cd src
-bash: cd: src: No such file or directory
[kpatel@sol25 .git]$ cd kpatel
-bash: cd: kpatel: No such file or directory
[kpatel@sol25 .git]$ cd Repo1
-bash: cd: Repo1: No such file or directory
[kpatel@sol25 .git]$ cd Repo1
-bash: cd: Repo1: No such file or directory
[kpatel@sol25 .git]$ git init
Reinitialized existing Git repository in /users1/st/kpatel/.git/.git/
[kpatel@sol25 .git]$ git add Helloworld.java
fatal: pathspec 'Helloworld.java' did not match any files
[kpatel@sol25 .git]$ cd
[kpatel@sol25 ~]$ cd /users1/st/kpatel/.git/.git/
[kpatel@sol25 .git]$ add Helloworld.java
bash: add: command not found...
[kpatel@sol25 .git]$ git add Helloworld.java
fatal: This operation must be run in a work tree
[kpatel@sol25 .git]$ git init
Initialized empty Git repository in /users1/st/kpatel/.git/.git/.git/
[kpatel@sol25 .git]$ git add Helloworld.java
fatal: pathspec 'Helloworld.java' did not match any files
[kpatel@sol25 .git]$ cd
[kpatel@sol25 ~]$ cd
[kpatel@sol25 ~]$ cd
[kpatel@sol25 ~]$ cd
[kpatel@sol25 ~]$ ls
cs3115          krunalpatel  lab4.save    lab4.save.2  phonebook0.java  Sum.java
HelloWord.java  lab4         lab4.save.1  lab4.save.3  REAME.md
[kpatel@sol25 ~]$ git add HelloWorld.java
fatal: pathspec 'HelloWorld.java' did not match any files
[kpatel@sol25 ~]$ ls
cs3115          krunalpatel  lab4.save    lab4.save.2  phonebook0.java  Sum.java
HelloWord.java  lab4         lab4.save.1  lab4.save.3  REAME.md
[kpatel@sol25 ~]$ git add HelloWorld.java
fatal: pathspec 'HelloWorld.java' did not match any files
[kpatel@sol25 ~]$ git add helloworld.java
fatal: pathspec 'helloworld.java' did not match any files
[kpatel@sol25 ~]$ ls
cs3115          krunalpatel  lab4.save    lab4.save.2  phonebook0.java  Sum.java
HelloWord.java  lab4         lab4.save.1  lab4.save.3  REAME.md
[kpatel@sol25 ~]$ add HelloWord.java
bash: add: command not found...
[kpatel@sol25 ~]$ git add HelloWord.java
[kpatel@sol25 ~]$ git commit  -m
error: switch `m' requires a value
usage: git commit [options] [--] <pathspec>...

    -q, --quiet           suppress summary after successful commit
    -v, --verbose         show diff in commit message template

Commit message options
    -F, --file <file>     read message from file
    --author <author>     override author for commit
    --date <date>         override date for commit
    -m, --message <message>
                          commit message
    -c, --reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --reuse-message <commit>
                          reuse message from specified commit
    --fixup <commit>      use autosquash formatted message to fixup specified commit
    --squash <commit>     use autosquash formatted message to squash specified commit
    --reset-author        the commit is authored by me now (used with -C/-c/--amend)
    -s, --signoff         add Signed-off-by:
    -t, --template <file>
                          use specified template file
    -e, --edit            force edit of commit
    --cleanup <default>   how to strip spaces and #comments from message
    --status              include status in commit message template
    -S, --gpg-sign[=<key id>]
                          GPG sign commit

Commit contents options
    -a, --all             commit all changed files
    -i, --include         add specified files to index for commit
    --interactive         interactively add files
    -p, --patch           interactively add changes
    -o, --only            commit only specified files
    -n, --no-verify       bypass pre-commit hook
    --dry-run             show what would be committed
    --short               show status concisely
    --branch              show branch information
    --porcelain           machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    --amend               amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)

[kpatel@sol25 ~]$ git commit m "finish up"
error: pathspec 'm' did not match any file(s) known to git.
error: pathspec 'finish up' did not match any file(s) known to git.
[kpatel@sol25 ~]$ git commit -m "finish Up"
[master (root-commit) 0dcfdef] finish Up
 20 files changed, 278 insertions(+)
 create mode 100644 .bash_history
 create mode 100644 .bash_profile
 create mode 100644 .bashrc
 create mode 100644 .cache/abrt/lastnotification
 create mode 100644 .local/share/keyrings/login.keyring
 create mode 100644 .local/share/keyrings/user.keystore
 create mode 100644 .oracle_jre_usage/8b2f0f5b19cf90f2.timestamp
 create mode 100644 HelloWord.java
 create mode 100644 Sum.java
 create mode 100644 cs3115/HelloWord.java
 create mode 100644 cs3115/HelloWorld.java
 create mode 100644 cs3115/temp
 create mode 100644 cs3115/temp.txt
 create mode 160000 krunalpatel
 create mode 100644 lab4
 create mode 100644 lab4.save
 create mode 100644 lab4.save.1
 create mode 100644 lab4.save.2
 create mode 100644 lab4.save.3
 create mode 100644 phonebook0.java
[kpatel@sol25 ~]$ git remote add Repo1 https://github.com/krunalpatel5678/Repo1
[kpatel@sol25 ~]$ git push github master
fatal: 'github' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
[kpatel@sol25 ~]$ git push -u repo1 master
fatal: 'repo1' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
[kpatel@sol25 ~]$ git push Repo1 master
Username for 'https://github.com': krunalpatel5678
Password for 'https://krunalpatel5678@github.com': 
Counting objects: 23, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (15/15), done.
Writing objects: 100% (23/23), 3.00 KiB | 0 bytes/s, done.
Total 23 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/krunalpatel5678/Repo1/pull/new/master
remote: 
To https://github.com/krunalpatel5678/Repo1
 * [new branch]      master -> master
[kpatel@sol25 ~]$ cd HelloWord.java
-bash: cd: HelloWord.java: Not a directory
[kpatel@sol25 ~]$ nano HelloWord.java
  GNU nano 2.3.1                 File: HelloWord.java                                        

impoert java.time.formate.DateTimeFormatter;
import.java.time.LocalDateTime;
public class HelloWord{
        public static void main(String [] args){
                System.out.println("Hello, World");

                DateTimeFormatter dtf=
                DateTimeFormatter.ofPattern("yyyy/MM/dd HH:mm:ss");
                        LocalDateTime now=
                        LocalDateTime.now();
                        System.out.println(dtf.format(now));
                                }
                        }





















                                     [ Wrote 13 lines ]

[kpatel@sol25 ~]$ git commit -m "finish up"
# On branch master
# Changes not staged for commit:
#   (use "git add <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#       modified:   .bash_history
#       modified:   .cache/abrt/lastnotification
#       modified:   HelloWord.java
#
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#       .gitconfig
#       REAME.md
no changes added to commit (use "git add" and/or "git commit -a")
[kpatel@sol25 ~]$ git add HelloWord.java
[kpatel@sol25 ~]$ git commit -m "Finish up"
[master 1464501] Finish up
 1 file changed, 12 insertions(+), 1 deletion(-)
[kpatel@sol25 ~]$ get remote add Repo1 https://github.com/krunalpatel5678/Repo1
bash: get: command not found...
Similar commands are::
'git'
'GET'
[kpatel@sol25 ~]$ git remote add Repo1 https://github.com/krunalpatel5678/Repo1
fatal: remote Repo1 already exists.
[kpatel@sol25 ~]$ git push -u repo1 master
fatal: 'repo1' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
[kpatel@sol25 ~]$ git push -u Repo1 master
Username for 'https://github.com': krunalpatel5678
Password for 'https://krunalpatel5678@github.com': 
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 467 bytes | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/krunalpatel5678/Repo1
   0dcfdef..1464501  master -> master
Branch master set up to track remote branch master from Repo1.


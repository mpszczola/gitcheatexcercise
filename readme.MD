1. Zarządzanie repozytorium
2. Dodawanie wpisów w historii

- Stwórz nowe repozytorium w którym umieścisz stworzony projekt
- Projekt powinien zawierać co najmniej 3 wpisy w historii
- Każdy wpis jest opatrzony Twoim imieniem oraz adresem email
- Dokonaj synchronizacji z zdalnym repozytorium w chmurze github.com
- 

=========================================================

ec2-user:~/environment $ cd ..
ec2-user:~ $ cd 201131
bash: cd: 201131: No such file or directory
ec2-user:~ $ cd environment/201131
ec2-user:~/environment/201131 (master) $ ls
alamakota.txt  creditcard-app  readme.MD
ec2-user:~/environment/201131 (master) $ ls
alamakota.txt  creditcard-app  gitcheat  readme.MD
ec2-user:~/environment/201131 (master) $ cd gitcheat
ec2-user:~/environment/201131/gitcheat (master) $ git init
Initialized empty Git repository in /home/ec2-user/environment/201131/gitcheat/.git/
ec2-user:~/environment/201131/gitcheat (master) $ git config user.name "Maria 
> ^C
ec2-user:~/environment/201131/gitcheat (master) $ git coonfig user.name "Maria Pszczola"
git: 'coonfig' is not a git command. See 'git --help'.

The most similar command is
        config
ec2-user:~/environment/201131/gitcheat (master) $ git config user.name "Maria Pszczola"                                         
ec2-user:~/environment/201131/gitcheat (master) $ git config user.email "mariapszczola@gmail.com"
ec2-user:~/environment/201131/gitcheat (master) $ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.MD

nothing added to commit but untracked files present (use "git add" to track)
ec2-user:~/environment/201131/gitcheat (master) $ git add readme.MD
ec2-user:~/environment/201131/gitcheat (master) $ git commit -m "Pierwszy commit"
[master (root-commit) 5777dd4] Pierwszy commit
 1 file changed, 7 insertions(+)
 create mode 100644 readme.MD
ec2-user:~/environment/201131/gitcheat (master) $ git remote add origin https://github.com/mpszczola/gitcheatexcercise.git
ec2-user:~/environment/201131/gitcheat (master) $ git push -u origin master
Username for 'https://github.com': mpszczola
Password for 'https://mpszczola@github.com': 
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 436 bytes | 436.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/mpszczola/gitcheatexcercise/pull/new/master
remote: 
To https://github.com/mpszczola/gitcheatexcercise.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
ec2-user:~/environment/201131/gitcheat (master) $ 
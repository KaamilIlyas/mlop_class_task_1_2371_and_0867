# mlop_class_task_1_r2371_and_0867

Git Commands to Merge and Commit to Main (Upstream Branch)

# For Master Branch

git checkout master   
git branch main master -f    
git checkout main  
git push origin main -f 

# For Test Branch 

git checkout test   
git branch main test -f    
git checkout main  
git push origin main -f 

# commands on terminal 
pwd
ls
git clone
touch requirements.txt
touch Makefile
touch Dockerfile
touch Jenkinfile
touch test.py
touch main.py

echo "this is mlops class repo" >> README.md
nano README.md
ctrl +o

git --version
git status
git add .
git reset HEAD Dockerfile (git reset HEAD .)

git commit -m "Initial commit"

git log

nano main.py
def getClassName ():
return "this is mlops class"
print (getClassName)

python main.py


git log
git diff -r (first 8 hash of one commit  and then the other commit to know about difference)

git config --global alias.ci 'commit -m'  (for commiting without writing commit)
nano main.py
(add something here extra)
ctrl o + enter
git add .
git ci "third commit"

git log -1 main.py  (recent commit)

git status
git checkout first 8 bits main.py
git clean -f main.py
ls

nano main.py
git checkout HEAD main.py
nano main.py

git branch
git checkout -b branch2
git branch
git branch -D branch2
git branch

nano requirements.txt
scikit-learn
pandas
numpy ctl +s

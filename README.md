# **STEPS**
 * create rep on [GitHub](https://github.com/)
 * create local rep
## *in local rep v1:*
1. git init
2. git status
3. create .gitignore
4. git add .
5. git commit -m"init: first commit"
6. git remote add origin http://your/github/rep/link
7. git push -u origin master

## *in local rep v2:*
1. delete .git dir
2. git clone origin http://your/github/rep/link in another dir
3. copy .git in project
4. git status
5. git add .
6. git commit -m"init: first commit"
7. git push
8. login-password

# **Create new-branch**
## **V1**
1. git branch new-branch
2. git checkout new-branch
## **V2**
1. git checkout -b new-branch

# **Generate dependence**

```
pip freeze > requirements.txt
```
# **Setup requirements**

```
pip install -r requirements.txt 
```

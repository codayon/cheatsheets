## git commands with little description

generate ssh key

```
ssh-keygen -t ed25519 -C "[valid-email]"
```

git user global config

```
git config --global user.name "[firstname lastname]"

```

git email global config

```
git config --global user.email "[valid-email]"
```

initialize git inside a folder

```
git init
```

add a remote and it's alias

```
git remote add [alias] [repo.url]
```

add one or multiple files to commit

```
git add [location/of/those/files]
```

add all changes to commit

```
git add .
```

commit to push

```
git commit -m "[message]"
```

rename git branch

```
git branch -M [branch]
```

push commit to the repository

```
git push -u [alias] [branch]
```

description for flags and my comments

`[alias]` it is the name for repo.url  
`[branch]` name of the branch  
`[message]` comment for commit and whatever was changed in that commit  
`[repo.url]` it refers to the url of repository  
`[valid-email]` the email you used in your github account  
`[firstname lastname]` it could be full name or `[username]` of your github account

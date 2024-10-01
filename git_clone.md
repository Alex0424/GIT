# Git Clone

generate a new ssh key:
```
ssh-keygen -t ed25519 -C "your_email@example.com"
cat cat ~/.ssh/id_ed25519.pub
```
on github.com --> settings/ssh --> New SSH Key --> paste your public ssh key here

make sure ssh-agent is running and add ssh key to ssh-agent:
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/<private_key>
```

```
git clone URL
```

# home
An example of my home directory. To init in a non-empty home directory:

```
cd ~
git init
git remote add origin https://github.com/matthew-a-spalding/home.git
git fetch
git checkout -t origin/master
cp skel/bashrc-vagrant .bashrc
source .bashrc
```

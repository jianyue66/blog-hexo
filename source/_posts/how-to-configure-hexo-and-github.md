---
title: how to configure hexo and github
date: 2020-02-22 21:33:50
tags: 
    - hexo
    - software
    - github
---
1. Configure your ssh.
Run
```
ssh-keygen -t rsa -C "your.email.com"
```
and copy all text except `"your.email.com"` in `~/.ssh/id_rsa.pub`.
Open github setting ssh
add new ssh key
input your text.
done.
2. Configure your hexo.
```
npm install hexo-deployer-git --save
```
and add
```
deploy: 
  type: git
  repo: https://github.com/xxx/xxx.git
  branch: master
```
3. Use it!!!
```
hexo clean
hexo g
hexo d
```

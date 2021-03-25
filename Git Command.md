# Git Command

```
git add .

git commit -m "first commit"

git remote add origin https://github.com/

git branch -M main

git push -u origin master

#LF will be replaced by CRLF
git config core.autocrlf true

```



```
问题:
 git push -u origin main
fatal: unable to access 'https://github.com/Amsia/DrealityArt.git/': OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 10054
解决(具体哪个不懂):
git config http.postBuffer 524288000
git config http.sslVerify "false"
git config --global http.sslVerify "false"



```




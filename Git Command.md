# Git Command

```
#创建仓库与上传
git add .

git commit -m "first commit"

git remote add origin https://github.com/

git branch -M main

git push -u origin master


#修改与上传
git add .
git commit -m 'note'
git push
=>git commit -am  (add&commit)

```



```
问题1:
 git push -u origin main
fatal: unable to access 'https://github.com/Amsia/DrealityArt.git/': OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 10054
解决(具体哪个不懂):
git config http.postBuffer 524288000
git config http.sslVerify "false"
git config --global http.sslVerify "false"
问题2
LF will be replaced by CRLF
解决
git config core.autocrlf true

取消弹出框验证用户名密码
it config --system --unset credential.helper




```




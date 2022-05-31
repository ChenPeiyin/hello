- 如果你的电脑是第一次使用的话，执行这句，然后将生成的密钥添加到你的 github 账户
ssh-keygen -t rsa -C "YOUR EMAIL"

- 拉取别人的工程
git clone [YOUR SSH]

- 拉取完之后：
git init
git add .
git commit -m "YOUR history"

- 第一次上传时，执行下面这句：
git push --set-upstream origin master
- 或者：
git remote add origin git@github.com:ChenPeiyin/hello.git



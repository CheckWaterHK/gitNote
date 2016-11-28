## Git命令
1.    git --bare init
>    
>    将本地文件夹变为一个Git仓库
>    

2.    ssh -keygen -rsa -t -C 'example@example.com'
>    
>    生成密钥和公钥
>    

3.    git add
>    
>    添加修改文件，匹配正则表达式
>     
>    *git add* 添加所有
>     
>    *git add \*.txt* 添加所有txt文件
>     

4.    git clone  \<name\> \<url\> \<directory\>
>    
>     克隆项目,name和directory可空
>    

5.    git remoteadd  \<name\>  \<url\>
>    
>     添加远程仓库,name可以随便取,url必须真实存在

5.    git status
>    
>     查看文件状态

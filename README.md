# GradientScript
Gradient 挂机脚本


## 使用教程
### 获取账号Token
> 登录网站 > 对着浏览器 按F12 > 找到网络 > 复制 authorization 内容 不要Bearer

![image](https://github.com/user-attachments/assets/906b17c7-1996-4809-b7de-21e9a2f02fc0)

> 使用软件获取账号密码
> ./Gradient-Token.exe -t [刚刚复制的内容]

![image](https://github.com/user-attachments/assets/35076925-1bb8-417c-bf09-b4323dc89d39)

## 生成配置文件
> config/proxy.ini 存放代理 一行一条 只支持http/https
> 格式：http://user@pass@ip:port

![image](https://github.com/user-attachments/assets/89387bbe-f861-40bd-a304-78ed7f54d502)

> 生成配置： ./Gradient-Tools.x64_linux -g [账号]:[密码]   刚刚脚本算出来的

![QQ_1728878388886](https://github.com/user-attachments/assets/9fd29750-a795-4ec9-a3c4-a7a11ba1f847)

## 节点启动 和 维护
> 说明 上面生成的 runc.sh 就是 如果需要分开多个账号 只需把 runc.sh 改为其他的文件名即可 
> 功能 启动节点 和 Kill 节点
> 1.启动所有节点 ./[sh文件名] start
> 2.结束单个节点进程 ./[sh文件名] kill [客户端ID]
> 3.结束所有节点 pkill -f Gradient-Tools.x64_linux

![image](https://github.com/user-attachments/assets/ff81c50f-0dd9-4410-bab9-af2857f55cae)


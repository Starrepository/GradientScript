# GradientScript
Gradient 挂机脚本
TG群：https://t.me/Web3um


## 使用教程
### 配置文件教程
- KEY授权码
- 其他的顾名思义
- NodesCount 账号1 节点数量

![image](https://github.com/user-attachments/assets/bd965bb6-e09d-4353-bef9-5515e9444475)

如果多个账号只需要复制USER 1内容 
![image](https://github.com/user-attachments/assets/0e2fdf6a-1807-4e12-a7d2-4d7225a13c61)

> proxy.ini 存放代理  一行一条 只支持http/https
> 格式：http://user@pass@ip:port

![image](https://github.com/user-attachments/assets/89387bbe-f861-40bd-a304-78ed7f54d502)

## 运行
参数 -gg 即可
```shell
./Gradient-Tools.x64_linux -gg
```
## 节点启动 和 维护
> 说明 上面生成的 runc.sh 就是 如果需要分开多个账号 只需把 runc.sh 改为其他的文件名即可
- 功能 启动节点 和 Kill 节点
- 1.启动所有节点 ./[sh文件名] start
- 2.结束单个节点进程 ./[sh文件名] kill [客户端ID]
- 3.结束所有节点 ./[sh文件名] killall

![image](https://github.com/user-attachments/assets/ff81c50f-0dd9-4410-bab9-af2857f55cae)


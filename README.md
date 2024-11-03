# GradientScript
Gradient 挂机脚本
TG群：https://t.me/Web3um

另外出售 双ISP节点 8r

## 功能
- 支持HTTP / HTTPS / Socks5 代理
- 解除对电脑性能的限制（1g1h 照样跑几千节点）
- 支持多平台系统

## 效果图片
![telegram-cloud-photo-size-1-4904524851994279271-y](https://github.com/user-attachments/assets/05a60a43-1436-4cab-9a0b-059fc659ea5a)
![image](https://github.com/user-attachments/assets/f184bd0b-f31e-4b92-9cfd-fb33d65c4829)



## 使用教程
### 配置文件参数说明

## 基本配置 (Config)

| 参数名 | 说明 | 示例值 |
|--------|------|--------|
| Key | 系统授权码，用于验证系统使用权限 | "" |
| Thread | 并发线程数，控制同时执行的任务数量 | 10 |
| ProxyApi | 动态代理API地址，用于获取动态代理服务 | "" |
| ProxyMode | 代理模式选择:<br>- static: 使用静态代理<br>- dynamic: 使用动态代理 | "static" |
| UserFile | 用户配置文件路径 | "config/users.txt" |
| TaskFile | 任务配置文件路径 | "config/task.txt" |
| ProxyFile | 代理服务器配置文件路径 | "config/proxy.txt" |

## 文件说明

- **users.txt**: 存储用户相关的配置信息
- **task.txt**: 存储需要执行的任务配置信息
- **proxy.txt**: 存储静态代理服务器列表

## 使用建议

1. 首次使用时需要确保填写正确的授权码（Key）
2. 根据系统性能和需求调整Thread值
3. 如果使用动态代理，需要在ProxyApi中填写有效的API地址
4. 确保所有配置文件路径正确且文件存在

## 代理模式选择

- 使用静态代理时：
  - 将ProxyMode设置为"static"
  - 在proxy.txt中配置代理服务器列表

- 使用动态代理时：
  - 将ProxyMode设置为"dynamic"
  - 在ProxyApi中填写动态代理获取接口


## 节点启动 和 维护
> Windows 就用 Win.bat \ Linux --> Linux.sh \ MacOs --> Mac.sh
>
> 
> (Linux例子)第一次使用 配置文件和代理修改好之后 运行 ./Linux.sh 运行后看图下的操作，简单明了

![image](https://github.com/user-attachments/assets/1c5ede6d-876f-48f5-9f4a-a0bc6a891520)

### 详细教程 （Windows为列 其他平台都一样）
## 首次使用 需要生成 节点信息
> 1. 修改 users.txt

- 格式 : 账号:密码:节点数量 一行一个

![image](https://github.com/user-attachments/assets/0913d791-b50e-49da-9dbb-824c5d9da4e2)

> 2. 添加代理

- 支持所有通用的代理格式
- eg: socks5://127.0.0.1:1080 、socks5://user:pass@127.0.0.1:1080
- eg: http(s)://127.0.0.1:1080 、http(s)://user:pass@127.0.0.1:1080

注意分配足够的代理

![image](https://github.com/user-attachments/assets/b0b7702b-a473-414c-bb2f-5e1e4d99325f)

> 3. 使用脚本运行&维护

第一次运行 Win.bat 选择 1 生成节点信息
![image](https://github.com/user-attachments/assets/39f1bf88-16c2-4085-b715-c52b21b561d1)

运行成功后 会在 config目录生成一个 挂机账号.txt 这个就是你的节点信息了，后面维护就也只维护这个

* 把挂机账号.txt的内容复制到task.txt *
* 然后运行 2 就可以跑节点内容了
* 注意 task.txt内容可以不修改，每次生成的挂机账号添加进去就可以了

![image](https://github.com/user-attachments/assets/1f3b8b45-4759-4e97-b4b5-2396c64f361c)



  




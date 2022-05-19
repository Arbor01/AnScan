# AnScan
AnScan是一款集信息收集、资产扫描/管理，分布式主动/被动漏洞扫描、POC插件管理、目录扫描、端口扫描、指纹识别等为一体的红队扫描工具。

AnScan项目目前已完成基本功能，对应的POC插件库AnPoc也在逐步收集构建中，后续都会开源～

感谢大家关注，开源时间可能会推迟一段时间(六,七月份～)，目前该项目正在公司内部测试使用，等所有功能都完善和稳定后会开源～

如果您有一些功能上的建议，可以提交issues或者在公众号：安不识TM，进行留言。

### 登录页面
![image](https://user-images.githubusercontent.com/29480790/154806457-83785b72-8f02-4b61-975c-f87379a807f2.png)

### 资产组管理
对扫描的资产进行分组管理，点击新建资产组新建资产
![image](https://user-images.githubusercontent.com/29480790/167071806-67309760-2d52-4fe7-a5db-4989be2b2a70.png)

查看资产组内的资产
![image](https://user-images.githubusercontent.com/29480790/167072237-e5af9083-a68e-45e0-9e41-734df9a9cb34.png)

点击主机名查看资产详情
![image](https://user-images.githubusercontent.com/29480790/167073396-0513c41d-68ce-4514-874c-dec841ff5d5f.png)

### 资产发现
新建资产发现任务，收集目标资产的组织架构、子域名信息
![image](https://user-images.githubusercontent.com/29480790/167073217-4a5950c2-24ca-4d3d-8b07-78876a49d4ed.png)

组织架构信息
![image](https://user-images.githubusercontent.com/29480790/167082126-157239d5-2d4d-435b-966a-ed8f94237d82.png)

域名信息
![image](https://user-images.githubusercontent.com/29480790/167072643-1fe4f99e-87b2-4077-bb82-3297b5b1d04b.png)

子域名详情
![image](https://user-images.githubusercontent.com/29480790/167073052-56fa0093-0fd0-4fdf-9342-dce1b201c13e.png)

### 资产扫描
资产扫描任务列表
![image](https://user-images.githubusercontent.com/29480790/167073268-2addf956-7f5b-4f13-bf37-496bc34c4703.png)

新建资产扫描任务，支持域名、IP段扫描，支持分布扫描，支持获取资产Web信息、网页截图、CDN检测，指纹识别、端口扫描、目录扫描、支持根据指纹识别检测漏洞
![image](https://user-images.githubusercontent.com/29480790/167073286-79a5fb19-cbf8-4a2a-a3ea-e1632e0236c0.png)

资产扫描任务详情
![image](https://user-images.githubusercontent.com/29480790/167073509-fa8cb4d6-6b5a-48a9-8fc7-edaf8f4fafcf.png)

资产扫描结果详情
![image](https://user-images.githubusercontent.com/29480790/167073396-0513c41d-68ce-4514-874c-dec841ff5d5f.png)

### 漏洞扫描

漏洞扫描，支持分布式扫描。
![image](https://user-images.githubusercontent.com/29480790/150317609-e5aaa6ba-e62d-45be-aae9-7bb775d20f6a.png)

### 漏洞扫描结果
![image](https://user-images.githubusercontent.com/29480790/150317267-fdc9284d-feac-48d4-878b-325a2c2f5013.png)
![image](https://user-images.githubusercontent.com/29480790/154090129-c4871a16-e8c1-4c3d-b39c-7b43ef0c92f1.png)

### POC插件列表
![image](https://user-images.githubusercontent.com/29480790/169247918-5501f881-ae57-49f1-a349-5297fae61808.png)

### POC详情
![image](https://user-images.githubusercontent.com/29480790/167084394-de9d6136-0072-4f98-93b7-c9880903e126.png)

### 指纹识别
![image](https://user-images.githubusercontent.com/29480790/167085155-00630861-91bc-4b66-8aa7-f0789ff5be0e.png)

### 命令备忘（交互逻辑参考谷歌插件Hack Tools）
![image](https://user-images.githubusercontent.com/29480790/167073614-fc797f81-fdf2-4c12-b87a-c5ef6e30dcb2.png)


[![Stargazers over time](https://starchart.cc/Arbor01/AnScan.svg)](https://starchart.cc/Arbor01/AnScan)

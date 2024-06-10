# Z-Godzilla_ekp
### 哥斯拉webshell二次开发规避流量检测设备  

二开详细教程在微信公众号：艾克sec  
目前测了国内两安全厂商的态感，连接和执行命令无告警  
~~现在改了php和java的，后续尽快新增net的~~   
java，net，php 流量修改已经全部支持，以后还会集成一键免杀功能和一些插件
觉得好用的师傅点点star～(更新的动力！！！)
#### 1.1更新
许多师傅提出市面上net webshell免杀工具较少，想隐匿流量却对默认生成的shell不会免杀，这里首先更新一下net的生成即免杀（后续推出其他语言的免杀以及随机html流量，最近很多攻防，还有学校的考试课，太忙了，师傅们体谅一下）  
使用方法：  
生成webshell选择bypass1(尽量不要用默认密码密钥，安天的引擎只要你输入pass和key就报红，aspx的马报jspwebshell就很离谱。。。）   
<img width="640" alt="图片" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/87b86418-ad9f-49f7-bc4c-00e8634654c4">  
即可免杀(vt 微步 阿里云 河马等均0报红)   
<img width="1444" alt="图片" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/6d4780ba-c322-4bd9-b303-f489e2441f17">  
<img width="697" alt="图片" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/e56e264d-a23c-4953-bcb4-123f54114bf8">
<img width="697" alt="图片" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/a732cd0e-f2b8-4973-9899-cd3ca1d49ac6"> 
<img width="705" alt="图片" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/1ac7d306-1da7-4d4b-ac44-3fc2f23c5ed8">


#### 流量修改效果
phpxorbase64流量修改前
<img width="948" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/5b38b145-5bfd-4c17-a7fc-f48cc7de58d8">  
修改后  
<img width="634" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/fa5e98ee-1989-4566-a2b9-4a623cb55305">   
java AESbase64流量修改前  
<img width="917" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/7482473d-20a2-43bc-b648-0bdcf52e93a7">  
java AESbase64流量修改后
<img width="1102" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/f3f0243b-5b79-4887-a7d5-999463723107">  

#### 使用方法：  
直接生成webshell再用网上的工具或者自己的免杀方法进行免杀（后续可能会提供一键免杀的功能）  
<img width="539" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/89f98872-ff73-482b-8f2f-efa7a08d95f0">  
连接时也选择对应的模式  
<img width="534" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/1e4b9104-524f-4fde-9916-374f6e947f06">  
命令执行一切正常  
<img width="643" alt="image" src="https://github.com/kong030813/Z-Godzilla_ekp/assets/97926809/3f76318e-2e03-496f-bfbf-112080d47d11">  

注：使用二开版本生成的webshell，用普通版本的哥斯拉是连不上的（选项中需要选择二开版本模式进行连接）

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=kong030813/Z-Godzilla_ekp&type=Date)](https://star-history.com/#kong030813/Z-Godzilla_ekp&Date)










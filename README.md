# Barrycca.github.io
访问链接：https://colab.research.google.com/drive/10sTG_7GLnKOokuWzuxBho6BNBBDy85XR?usp=sharing


功能说明：
discord自动聊天机器人，
可配置多个聊天频道同时聊天，
可配置发送的时间（范围随机），
随机发送自定义语句的其中一条，
配置是否开启发送币种最新价格，使用的是okx的api，
可配置查询交易对最新价格列表，
交易对价格发送概率（具体语句模板需要自己滚上去自己改改）


操作步骤
1.首先你要有一个谷歌账号，打开链接，点击左上角 文件-在云端硬盘中保存一份副本，生成你的专属脚本,收藏这个网址。


2.关键配置![image](https://github.com/Barrycca/Barrycca.github.io/assets/25716101/5e94d7c9-ef99-4f1d-b363-2dda10bc1b60)

id,聊天频道，打开discord，选择你要自动发送消息的频道
![image](https://github.com/Barrycca/Barrycca.github.io/assets/25716101/6d17ac4c-03a7-41f0-a59d-584b459e2450)

authorization_list，登录凭证，打开discord，按F12打开调试工具-点击Network-在Name里随便选一个接口（如果没有就在频道随便打一下字）-Request Headers-Authorization-复制
这个登录凭证一年半载都不会变得，除非你注销登录之类的，所以复制一次就可以了，如果突然有一天发现运行起来没效果可以再来看看是不是变了，替换就行
![image](https://github.com/Barrycca/Barrycca.github.io/assets/25716101/0ae5d2d9-fb76-44c9-8e66-04da0e21eb34)


3.自定义内容，可以自己总结一些常发的话，也可以用chatgpt帮你生成，自己发挥想象可以是废话，表情，笑话...建议不要用代码默认的句子，太多人用一用的就GG
![image](https://github.com/Barrycca/Barrycca.github.io/assets/25716101/803efa93-1b50-4b85-9cad-8e9f5d8a17f5)
![image](https://github.com/Barrycca/Barrycca.github.io/assets/25716101/4ec336e4-1bea-410c-9fc0-205f1589f327)

配置完就可以点左上角的播放按钮了，开启你的自动聊天之旅

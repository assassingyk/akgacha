# akgacha
arknights gacha simulator for hoshinobot
author: 库兰 - NGA romanosovsky

使用方法
======
[@Bot 方舟十连] 明日方舟抽卡
[@Bot 方舟来一井] 300抽
[查看方舟卡池] 当前卡池信息
[切换方舟卡池] 更改卡池，如果不加卡池名则会列出当前卡池列表

安装
======
- 将本项目放在hoshino/modules/目录下
- res.zip为头像数据，解压在Hoshino根目录下(头像路径为res/img/akgacha/*.png)

说明
======
- 如果碰到找不到json文件的问题，尝试调整代码的working_path字符串。这部分还在调整中
- 卡池数据在config.json中，可以在项目目录下运行generate_config.py生成。（up谁需要自己填写）

---
share: true  
---
## 第 0 步——安装和激活 rewasd
1. 运行赠品文件夹下的 `reWASD651最新版安装包.exe`，安装完毕后，重启电脑。
2. 打开 [点我进入官网购买正版rewasd](https://www.daemon-tools.cc/chn/cart) ，支持微信与支付宝，==全价 118 r==，
	- 也可选择闲鱼上的盗版，约为 50 r。
	- 也可不购买，==有 3 天免费体验时间==。
## 第 1 步——运行灵敏度自动修改软件
1. 运行如图所示的软件 
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679065776000seavr8.png)
2. 输入你自己的鼠标 dpi 灵敏度, 然后回车：
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679065955000kc447h.png)
	- 雷蛇鼠标 dpi 参见下图：
		- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679066040000nza8ia.png)
3. ==!!! 仔细检查软件读取的灵敏度是否正确!!!==，不正确输入 0，正确输入 1。
	- ==**很多人用过改 0.2 灵敏度的宏，此时不要输入 1，输入 0，然后输入自己正确的灵敏度。**==
	- 若输入 1，软件会自动调节好数据并打开 rewasd 导入数据
	- 若输入 0，请输入自己的正确灵敏度数值，然后软件同样会==自动修改并导入==
		- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679067599000srr6qy.png)
## 第 2 步——修改游戏 cfg 设置
1. 按 win+r 打开运行
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679068079000jqlt23.png)
2. 粘贴 `"C:\Users\%USERNAME%\Saved Games\Respawn\Apex\local\settings.cfg"` 后回车。
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679068175000cxz90k.png)
	- 或者手动打开
		- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679068494000bjr9k7.png)
3. 打开后应该如图所示：
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679068736000uus5gi.png)
4. 将下列代码放到==文件末尾==：
```
bind_US_standard "o" "exec sen1.cfg" 0
bind_US_standard "p" "exec sen2.cfg" 0
```
![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679068892000sf8r53.png)
## 第 3 步——放入 sen 文件
1. 运行完 `自动修改灵敏度程序.exe` 后，软件会生成一个 `sen2.cfg` 文件。
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679069480000jusnln.png)
2. 把 `sen1.cfg` 和 `sen2.cfg` 俩个文件放入==游戏根目录中的 `cfg` 文件夹==中
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679069594000422knl.png)
	- ![gh](https://raw.githubusercontent.com/zxmengde/obsidian-emo/main/image/1679069656000fjp9qc.png)
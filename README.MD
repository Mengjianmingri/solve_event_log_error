## 解决启动安卓模拟器时十个event log error
### 打开终端按行输入命令
	sudo apt install mesa-vulkan-drivers
	sudo add-apt-repository ppa:kisak/kisak-mesa
	sudo apt update
	sudo apt upgrade
	sudo gedit ~/.android/advancedFeatures.ini
### 填入以下保存后重启系统
	Vulkan = off
	GLDirectMem = on

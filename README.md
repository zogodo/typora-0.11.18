# Typora-0.11.18 最后一个免费版本

## Typora-0.11.18 The last free version

点击下载对应版本:

Click to download:

[![win64](https://img.shields.io/badge/Windows%20(64bit)-exe-blue)](https://github.com/zogodo/typora-0.11.18/raw/master/typora-setup-x64-0.11.18.exe)　[![win64](https://img.shields.io/badge/Windows%20(32bit)-exe-blue)](https://github.com/zogodo/typora-0.11.18/raw/master/typora-setup-ia32-0.11.18.exe)

[![win64](https://img.shields.io/badge/Linux%20(amd64)-deb-brightgreen)](https://github.com/zogodo/typora-0.11.18/raw/master/typora_0.11.18_amd64.deb)　[![win64](https://img.shields.io/badge/Linux%20(x64)-tar-brightgreen)](https://github.com/zogodo/typora-0.11.18/raw/master/Typora-linux-x64-0.11.18.tar.gz)　[![win64](https://img.shields.io/badge/Linux%20(arm64)-deb-brightgreen)](https://github.com/zogodo/typora-0.11.18/raw/master/typora_0.11.18_arm64.deb)

[![win64](https://img.shields.io/badge/MacOS-dmg-orange)](https://github.com/zogodo/typora-0.11.18/raw/master/Typora-0.11.18.dmg)

---

# Typora-0.11.18 报错处理

安装后打开会弹窗报错:

![error](doc/error.png)

原因是因为 Typora-0.11.18 是免费版, 在系统注册表中记录了一个最后使用时间, 超过将无法使用.



# 解决办法

1. 打开注册表：按 `Win` + `R` 键打开运行窗口，输入 ` regedit`

   ![win_run](doc/win_run.png) 

2. 进入路径 `计算机\HKEY_CURRENT_USER\SOFTWARE\Typora`

   ![regedit](doc/regedit.png) 

   ![permission](doc/permission.png) 

设置好点【确定】后再打开 Typora 就可以啦~

---

感谢: [Typora 最后免费版本也不能用了？简单一招搞定](https://xiaoniuhululu.com/2022-07-28_Typora_isExpired_deal/)


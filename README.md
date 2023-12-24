# SHU-VPNconfig-for-Ubuntu

参照 https://vpn.shu.edu.cn/ 上的SHU.ovpn修改而来，原本的该文件无法直接导入Ubuntu的VPN设置。

修改后已在Ubuntu20.04与Ubuntu22.04上测试成功。



## 使用方法

以Ubuntu22.04为例，Ubuntu20.04与其他相近版本类似。

1. 下载本repo的 `SHU-VPN-Ubuntu.ovpn` 到本地。

2. 打开Ubuntu设置，找到 `Network - VPN` ，点击右侧加号，如图：

   <img src="https://raw.githubusercontent.com/SHUzhekiNg/SHUzhekiNg.github.io/main/assets/typoraimages/image-20231224142949431.png" alt="image-20231224142949431" style="zoom:80%;" />

3. 点击下方 `Import from file...` ***#注意不是第一个OpenVPN#***，选择本地已下载好的 `SHU-VPN-Ubuntu.ovpn`
   <img src="https://raw.githubusercontent.com/SHUzhekiNg/SHUzhekiNg.github.io/main/assets/typoraimages/image-20231224143245970.png" alt="image-20231224143245970" style="zoom:80%;" />

4. 在下图对应位置填写本人学工号与统一认证密码。
   <img src="https://raw.githubusercontent.com/SHUzhekiNg/SHUzhekiNg.github.io/main/assets/typoraimages/image-20231224143500689.png" alt="image-20231224143500689" style="zoom:80%;" />

5. 添加后，打开即可连接。如图

![image-20231224143808459](https://raw.githubusercontent.com/SHUzhekiNg/SHUzhekiNg.github.io/main/assets/typoraimages/image-20231224143808459.png)
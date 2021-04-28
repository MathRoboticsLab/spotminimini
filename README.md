# Spotminimini

###### tags: `mrl` `robot` `tutorail`

## 事前準備
### 材料
#### 必要品


| 品項                             | 數量 | 價錢        | 備註     |
| -------------------------------- | ---- | ----------- | -------- |
| MG996R servo motor 90度          | 12   | 195(不含稅) |          |
| HC-SR04 Ultrasonic sensor        | 2    | 120         |          |
| MPU-6050 Gyro sensor or MPU-9050 | 1    | 99          |          |
| I2C 16x2 LCD Module              | 1    | 129         |          |
| Rleil rocker switch RL3-4        | 1    | 20          |          |
| 7.4v Battery                     | 1    |             | 實驗室有 |
| Raspberry Pi 3B+                 | 1    | 1505        |          |
| F625zz Flange ball bearing       | 8    | 110         |          |
| PCA9685                          | 1    | 286         |          |
| 5V/5A                            | 1    | 133         |          |
#### 消耗品


| 品項         | 數量 | 價錢 | 備註           |
| ------------ | ---- | ---- | -------------- |
| M5×15        | 8    |      |                |
| M4×20        | 40   |      |                |
| M4×15        | 8    |      |                |
| M4 nut       | 48   |      |                |
| M3×20        | 4    |      |                |
| M3×10        | 28   |      |                |
| M3 nut       | 16   |      | 螺絲共250      |
| 三秒膠+砂紙  | 1    | 95   |                |
| M3×25        | 8    |      |                |
| 麵包版+電線  | 1    | 250  |                |
| Flexible PLA | 1    | 330  | 顏色可以自己選 |

電子材料行
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_c2aa528b9dd9e98a226da35b81d000dd.png)
承軸
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_6da1faaa04e8f72ca6414d0605dc9c8f.png)
螺絲
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_f2ace12f458983db1910857cddb302ff.png)
剩下可上網購買
https://www.taiwaniot.com.tw/




### 3D列印
[原網址](https://www.thingiverse.com/thing:3445283 )
[檔案連結](https://drive.google.com/file/d/1NRVSzWPO_NljJa0uXyuZC-TMpqVH1S0P/view?usp=sharing)
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_1e78a6ff7a421c6ba8ad09e1504a08d6.png)
#### 切片
列印前必須將模型切片
[cura](https://ultimaker.com/software/ultimaker-cura)
再送到3D印表機
因好應如下圖
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_7e6f1f4c04b30954a8a2c5e92dbfc9ea.png)

[機器人進度IG](https://www.instagram.com/extraordinary_leon/)


最後 你必須要有耐心 因為要組10台，在說你小胖(王郁翔)，不是你啦酒鬼。

## 組裝

### 模型
1.先將中心部份組好如圖所示，使用M3螺絲及螺帽
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_6924b08acf3a3cd60a7465832b9037c7.jpg)

![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_4673ba33c6a2ddc1f49b1f879de37e42.jpg)

2.腳分為三個部件，小腿、大腿及關節
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_37a858f2f8f549b882aba0958a628895.jpg)
將馬達鎖上小腿
<img src="https://codimd.mcl.math.ncu.edu.tw/uploads/upload_ab2b6ab0794e82fbc803f040e24818a9.jpg" width=300>
將大腿上的關節用三秒膠黏上(黑色的那塊會附在馬達裡，可以用剪刀剪成適合的形狀)
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_2d5ff1b8295b5a8aeee8f54ed7b25d1b.jpg)

將線埋進凹槽裡
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_e650a34e877767c49c4ea21dc1d2511d.jpg)
將上蓋合緊，並將螺絲鎖上
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_2853207e79af47fa7f5edfe9f9311c78.jpg)
將馬達鎖上



![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_2c63faf28c86125da5d63942b0aa8e03.jpg)
用三秒膠黏上
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_0eb2b9d3e390338e51297cd4c146413a.jpg)
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_de2ada8b878137e4aaa2ec1c566b79f8.jpg)
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_bd11c15ef4da52e59dcb37dfb8b5eb81.jpg)



### 硬體
請將電池T接頭與3.5mmDC接頭焊在一起
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_0f8cdabf8b2adf12884399423a6715d9.jpg)
這樣連接
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_272a249caf951827a2372a8afa544a69.jpg)
![](https://codimd.mcl.math.ncu.edu.tw/uploads/upload_8473ade10f03dc02f054fd3caedbcf15.png)
請注意正負及千萬不要接反

## 軟體

https://github.com/mike4192/spotMicro
請參考此篇 

## 已知問題
### 12/30
PCA9685在推不動的時候會燒掉，不確定是不是跟降壓模組有關。
馬達接上去的時候要注意方向，可以先確定她得位置之後再鎖上去。

### 1/9
PCA9685 在馬達卡死時會燒掉，可能會稍電容跟IC，寒假完修。
校正不知為什麼沒有設定好，可能要手動調一遍。
電流可能不夠，有點撐不起來。




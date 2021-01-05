# ロボットシステム学課題1
---

動作環境
---
Ubuntu 18.04 LTS

---

概要
---
RaspberryPi4を用いてLEDを点灯させるデバイスドライバを作成した。

---

使用したもの
---
・RaspberryPi4

・ブレッドボード

・ジャンパーピン x2

・LED

・抵抗 200Ω

---

回路
---
<img src="https://user-images.githubusercontent.com/72175085/103672027-0bc8f800-4fbf-11eb-8984-c036b2c0d335.jpg" width="320px">

GPIO25とGNDの間にLEDと抵抗を接続する。

LEDのアノードはGPIO25に接続する。

---

実行方法
---

```
   $ git clone https://github.com/uvershuta/RobotSystem1.git
   $ cd myled
   $ make
   $ sudo insmod myled.ko
   $ sudo chmod 666 /dev/myled0
   ```
  
・点灯

`$ echo 1 > /dev/myled0`

・消灯

`$ echo 0 > /dev/myled0`

---

動画
---

---

ライセンス
---
[GNU General Public License v3.0](https://github.com/uvershuta/RobotSystem1/blob/main/COPYING)





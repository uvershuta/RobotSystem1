# ロボットシステム学課題1
---

動作環境
---
Ubuntu 18.04 LTS

---

実験概要
---
RaspberryPi4を用いてLEDを点灯させるデバイスドライバを作成した。

---

動画
---

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
![回路](https://user-images.githubusercontent.com/72175085/103672027-0bc8f800-4fbf-11eb-8984-c036b2c0d335.jpg)
---

実行方法
---
・点灯

`echo 1 > /dev/myled0`

・消灯

`echo 0 > /dev/myled0`

---

ライセンス
---
[GNU General Public License v3.0](https://github.com/uvershuta/RobotSystem1/blob/main/COPYING)





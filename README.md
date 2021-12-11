# myled
ロボットシステム学課題1
2021年度ロボットシステム学の課題1で作成したデバイスドライバです。

echo 1 > /dev/myled0　で点灯し、
echo 0 > /dev/myled0　で消灯します。

# 動作環境
Raspberry Pi 4 Model B

OS : ubuntu 20.04 server

使用したもの
Raspberry Pi 4 Model B × 1

LED × 1

抵抗400Ω × 4

ブレッドボード × 1

ジャンパー線（オス-メス）× 2

# 結果
https://www.youtube.com/watch?v=7Pz6e2-GdxM
# ライセンス
https://github.com/hellocit/myled/blob/main/COPYING
# 作成するにあたり引用したプログラム
https://github.com/ryuichiueda/robosys_device_drivers/blob/master/myled10.c

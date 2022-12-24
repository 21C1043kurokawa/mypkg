![test](https://github.com/21C1043kurokawa/robosys2022/actions/workflows/test.yml/badge.svg)
# mypkg
* ロボットシステム学の授業用ROS2パッケージ

# install
```
mkdor -p ~/ros2のワークスペース名/src
cd ~/ros2のワークスペース名/src
git clone https://github.com/21C1043kurokawa/mypkg.git
```
# 概要 
 * messageの通信方法 topic通信
 * publisher: /talker
 * subscriber: /listner
 * topic: /countup
 * messageの型: int16

# 実行
* /talker が数字をカウントし /countup を通じて送信、/listner がメッセージを受け取り表示
```
ros2 run mypkg talker
```
もう一つ端末を立ち上げてそこで
```
ros2 run mypkg listener
```

# 必要なソフトウェア
 * os
     * Ubuntu22.04.1 LTS
     * [download](https://jp.ubuntu.com/download)
 * ROS2
     * テスト済みバージョン： Humble
 * Python

# テスト済み環境
 * Ubuntu22.04.1 LTS

# LICENSE
 * このソフトウェアパッケージは、３条項BSDライセンスのもと、再配布および使用が許可されています。
 * © 2022 Daiki Kurokawa


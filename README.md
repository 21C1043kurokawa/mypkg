![test](https://github.com/21C1043kurokawa/robosys2022/actions/workflows/test.yml/badge.svg)
# mypkg
* ロボットシステム学の授業用ROS2パッケージ
* install
```
mkdor -p ~/ros2のワークスペース名/src
cd ~/ros2のワークスペース名/src
git clone https://github.com/21C1043kurokawa/mypkg.git
```
* 概要 
     * 通信方法 topic通信
     * publisher /talker
     * subscriber /listner
     * topic /countup
  * messageの型 int16
/talker が数字をカウントし /countup を通じて送信、/listner がメッセージを受け取り表示
* 




# RC_GDUT_ROBOT_SIMULATION
# 使用
观看ros教程 http://www.autolabor.com.cn/book/ROSTutorials/index.html

看完前六章并下载对应的依赖

在下载仓库后直接打开控制台运行`roslaunch robo_test.launch `

# 介绍

## 1. 场地

在RC_GDUT_ROBOT_SIMULATION中,场地目前设置为长方形木板地面


---

## 2. 机器人

使用https://github.com/6-robot/wpr_simulation.git中的机器人模型

1.机器人底盘为三全向轮，可通过对应的cmd#_vel话题控制速度

2.配备有imu. 可通过imu/data#话题获取数据

3.配备雷达，相机等设备，可供使用

---

## 3. 比赛系统（在构想中）
使用action通信来判断机器人是否到达另一端底部，以此实现自动判断比赛胜负

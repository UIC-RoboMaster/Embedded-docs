# 【烧仙草】Robomaster-Team Embedded DOC

## About Chassis

- 底盘任意电机掉线会导致底盘锁死，请检查电机对象的Uptime是否存在数值（代表着电机的启动时间）
- 电机的机械安装可能存在正向\反向，请根据实际情况考虑是否为电机附加`REVERSE_MOTOR`参数

## About Gimbal

- 云台的校准数据包位于`gimbal_data.h`文件中，数据来源详见gimbal.h和`gimbal_task.cpp`的定义

## RinChord’s Change

正在添加`config.h`配置文件，用于集中各种常见配置，通过简单地修改该文件，即可让一辆车快速地动起来。
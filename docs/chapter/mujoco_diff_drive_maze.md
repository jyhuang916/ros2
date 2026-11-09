# MuJoCo差速小车走迷宫仿真

## 实验目标

实现差速驱动小车在MuJoCo仿真环境中，按照固定开环路径走完预设直角迷宫轨迹。

## 模型参数

- 轮半径：0.05m
- 轮距：0.3m
- 原地转向角速度：0.333rad/s
- 转90度需要470步（仿真timestep=0.01s）

## 运行命令

```bash
cd src/diff_drive_maze
python3 main.py

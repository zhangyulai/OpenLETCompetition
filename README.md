# OpenLETCompetition 专家脚本演示

本仓库展示 OpenLET 三个仿真任务的专家脚本运行视频。机器人由官方专家脚本结合逆运动学与轨迹规划实时控制，在 MuJoCo 中完成任务。

## 任务视频

| 任务 | 视频 | 时长 | 本轮得分 |
| --- | --- | --- | --- |
| 任务 1：零件取放与拨杆 | [查看视频](./task1_parts_pick_expert.mp4) | 57.5 秒 | 100 |
| 任务 2：双臂协同搬箱 | [查看视频](./task2_box_move_expert.mp4) | 53.5 秒 | 100 |
| 任务 3：小件循环上料 | [查看视频](./task3_loop_feed_expert.mp4) | 50.1 秒 | 100 |

视频采用第三人称视角，已隐藏仿真侧边面板。格式为 H.264 MP4，分辨率 1280×720，帧率 30 fps，无音轨。

每个任务录制一轮，使用 `round=1`、`seed=28`，均成功完成。表中得分对应视频展示的单轮运行。

## 相关项目

- [官方仿真代码与场景](https://github.com/LejuRobotics/kuavo-ros-opensource/tree/opensource/openlet_embodied_ai_challenge_2026)
- [官方 LeRobot 数据集](https://atomgit.com/OpenLET/Embodied-Data-Manipulation-Challenge)

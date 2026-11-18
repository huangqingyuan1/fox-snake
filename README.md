# Snake 贪吃蛇

用 Godot 4.5 写的经典贪吃蛇，支持 Windows / Linux / Android。

## 玩法

- 32×32 地图，撞墙从对面穿出，咬到自己才结束
- 同时最多 5 个食物，吃掉补新
- 按住方向键加速 2 倍；手机上左轮盘转向、右加速键
- 空格暂停，F11 全屏，R 重来，M 回主界面

## 下载

到 [Releases](https://github.com/huangqingyuan1/fox-snake/releases) 下载：

- `Snake.apk` —— 安卓（Android 7.0+）
- `Snake-windows.zip` —— Windows x64，解压运行 `Snake.exe`
- `Snake-linux.zip` —— Linux x64，解压运行 `Snake.x86_64`

## 源码

`E:\Godot\02` 工程结构：`Scripts/Game.gd` 是全部游戏逻辑，`Scenes/Main.tscn` 是入口场景。

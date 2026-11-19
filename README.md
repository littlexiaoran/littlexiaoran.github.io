# LittleXiaoRan · 游戏门户

原创网页游戏的个人主页，收录所有已上线的游戏。

**主页地址：** https://littlexiaoran.github.io/

## 游戏

| 游戏 | 简介 | 在线游玩 |
| --- | --- | --- |
| 星环突围 · STAR RING BREAKOUT | 双摇杆竞技场射击：五波进攻、随机强化、动态首领 | https://littlexiaoran.github.io/star-ring-breakout/ |
| 67 射手 · 67 SHOOTER | 光标瞄准、长按连射的街机射击 | https://littlexiaoran.github.io/67-shooter/ |
| 抽签 · LUCK DRAW | 摇签解运，六档签文与签运统计 | https://littlexiaoran.github.io/luck-draw/ |
| 国际象棋 · CHESS | 双人对战、四档人机对战，完整规则 | https://littlexiaoran.github.io/chess/ |
| 3D 迷宫 · 3D MAZE | 第一人称迷宫，五关寻钥匙开门 | https://littlexiaoran.github.io/3d-maze/ |
| 英语听力模拟器 · EN-LISTEN-SIM | 上传音频、叠加五类噪音、本地导出 | https://littlexiaoran.github.io/en-listen-sim/ |

星环突围另有 itch.io 页面：https://littlexiaoran.itch.io/star-ring-breakout

## 主页说明

- `index.html` 为整站唯一文件，纯 HTML + CSS + 少量 JavaScript，无任何外部依赖
- 视觉风格取自《星环突围》：深空径向渐变底色、薄荷绿点缀、卡片式游戏入口
- 右上角按钮可切换中英文
- 游戏卡片直接链向各游戏的部署地址；新增游戏只需复制一张 `.game-card` 卡片
- `404.html` 为 GitHub Pages 的自定义 404 页面，风格与主页一致

## 本地预览

直接双击打开 `index.html`，或启动本地静态服务器：

```bash
python3 -m http.server 8000
```

然后访问 http://localhost:8000

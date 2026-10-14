# Claude-Codex pet

一个橘发、花饰、黑白橙裙装的傲娇大小姐 Codex 桌面宠物。嘴硬心软，会侧目看你、鼓嘴不服气，也会认真陪你工作。

**[下载宠物安装包](https://github.com/klu6163-droid/Claude-Codex-pet/releases/latest)**

## v1.0.1 更新

重绘向右跑的八帧步态，让双脚有更清楚的收回、抬起和向前迈出的交替变化。保留傲娇侧目，其余十行动作保持不变。

![向右跑动画](preview/running-right.gif)

## 动作总图

![Claude-Codex pet 动作总图](preview/contact-sheet.png)

包含抱臂待机、左右小跑、傲娇挥手、开心小跳、鼓嘴不服气、等待回应、认真思考、检查成果，以及 16 个注视方向。

## 安装

1. 从 Releases 下载 `Claude-Codex-pet-v1.0.1.zip` 并解压。
2. 将 `chengli-tsundere` 文件夹放入 `%USERPROFILE%\.codex\pets\`。
3. 在 Codex 的宠物列表中选择 **Claude-Codex pet**。如果列表没有刷新，重新打开 Codex。

安装后的目录结构：

```text
%USERPROFILE%\.codex\pets\chengli-tsundere\
├── pet.json
├── spritesheet.webp
├── README.md
└── 人设说明.md
```

内部 ID 保留为 `chengli-tsundere`。已有同 ID 宠物时，可先备份旧文件夹再替换。

## 动画预览

下载或克隆本仓库后，用浏览器打开 `preview/index.html`，可查看全部动作，并移动鼠标查看注视方向。该页面直接读取包内最终动画图。

## 格式

- Codex sprite version：`2`
- 动画图：透明 WebP，`1536 × 2288` 像素
- 布局：`8 × 11`，每格 `192 × 208` 像素
- 最终动画图 SHA-256：`4e57388458e3331bdfddda4e4f29233c85854e149593a28c454e3c485e11cc88`

角色外形参考由项目创建者提供，素材由 AI 图像工具生成，并经过动作筛选、边缘修复与排版验证。人设台词是创作说明；静态宠物包本身不会改变 Codex 助手人格，也不提供自动语音或对话。

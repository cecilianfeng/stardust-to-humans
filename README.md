# 从星尘到人类 · From Stardust to Humans

一部约 2 分钟的动画短片：从宇宙大爆炸、地球形成，到海洋、陆地和天空中的生命，最后到人类。

A ~2-minute animated short on the origin of the universe, Earth, life and humans.

**在线观看 / Watch:** https://cecilianfeng.github.io/stardust-to-humans/

## 作者说明 / Authorship

这部短片的代码全部由 Anthropic 的 AI 模型 Claude 编写。我提出了主题和需求（讲清楚宇宙、地球和生命的起源，涵盖海洋、陆地和天空中的生物），视觉风格、画面和代码由 Claude 完成。

All of the code in this project was written by Claude, an AI model by Anthropic, from my brief (explain where the universe, Earth, life and humans came from, covering sea, land and sky creatures). The visual style, scenes and code are Claude's work.

## 技术 / How it works

- 单个 HTML 文件，不用任何框架或外部库
- 画面全部用 **HTML5 Canvas 2D** 实时绘制，没有图片或视频素材
- 背景音乐和音效用 **Web Audio API** 实时合成
- 13 个场景排在一条时间轴上，每个场景是一个以「已播放时间」为参数的绘制函数，相邻场景交叉淡入淡出
- 用带固定种子的伪随机数生成星空、粒子和生物位置，每次播放画面一致
- 右上角的「地球一日钟」把地球 45.4 亿年的历史换算成 24 小时

The piece plays live in the browser and is not exported to a video file.

## 本地运行 / Run locally

直接用浏览器打开 `index.html` 即可。Open `index.html` in a browser.

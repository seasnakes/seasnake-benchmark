# SeaSnake Benchmark [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> SeaSnake 的个人 AI 能力测试用例合集：用真实的创作任务（动画、MV、片头复刻、TTS）检验各家大模型能做到什么程度。

每个用例都附上成品视频、源码或对话记录，方便复现和横向对比。

## 目录

- [动画 / MV 生成](#动画--mv-生成)
- [片头 / 开场动画复刻](#片头--开场动画复刻)
- [语音合成（TTS）](#语音合成tts)
- [参与贡献](#参与贡献)

## 动画 / MV 生成

- **world.execute(me); MV** · `Claude Opus 5.5` — 一句话提示词直接生成整支 MV，附完整对话过程记录。
  [视频](https://www.bilibili.com/video/BV1RHhU63ESq/) · [动画源码](https://github.com/seasnakes/world.execute-me-wallpaper)

## 片头 / 开场动画复刻

- **弹丸论破 2 开场动画（TOKEN 冒险岛）** · `GPT-6.1 SOL` — 经过十几轮对话完成复刻，并让模型额外做了一个可替换人物角色的编辑器。
  [视频](https://www.bilibili.com/video/BV1WYaU6oEJV/)
- **爱死机（Love, Death & Robots）片头** · `Claude Opus 5.5` — 一句话 zero-shot 复刻，含直出版、原片对照版、手动补全版三个分 P；模型会主动替换元素以避免一比一照搬。
  [视频](https://www.bilibili.com/video/BV11PpH6bEti/)

## 语音合成（TTS）

- **多玲国多语种 TTS 对比** — 多语种 TTS 试听对比，配合原片逐句对照。
  [仓库](https://github.com/seasnakes/duolingguo-tts-benchmark) · [试听主页](https://seasnakes.github.io/duolingguo-tts-benchmark/) · [逐句对照](https://seasnakes.github.io/duolingguo-tts-benchmark/aligned.html)

## 参与贡献

欢迎提 Issue 或 PR 补充新的测试用例。每条请注明：任务名称、所用模型、提示词轮数（一句话 / 多轮），以及成品或源码链接。

---

作者：[@seasnakes](https://github.com/seasnakes) · B 站 [SeASnAkEss](https://space.bilibili.com/486682682)

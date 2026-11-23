# 河图口播视频剪辑

给 Codex 一段真人口播和可选的逐字稿，用吴河图的剪法完成对白精剪、字幕、图解、拟音和导出。开场先看见人；动作跟着词出现，讲清楚就回到人。

## 看一个真实剪辑片段

[![从提问、日历图解到主播回弹的三个画面](examples/riemann/sequence.jpg)](examples/riemann/host-calendar-return.mp4)

[播放或下载 5.4 秒有声 MP4](https://raw.githubusercontent.com/wuhetu619-crypto/-/main/examples/riemann/host-calendar-return.mp4) · [逐帧节奏说明](skills/hetu-koubo-edit/references/riemann-beats.md)

这是《黎曼猜想》定稿里的一段连续镜头。河图问“它到底在问什么呢”，说到手机日历时缩到左侧，右侧图解完成后再弹回全屏。这里截取了原片中段；正式成片的开头还须遵守前三帧全屏真人的规则。

## 复制给 Codex 安装

> 请从 https://github.com/wuhetu619-crypto/-/tree/main/skills/hetu-koubo-edit 安装「河图口播视频剪辑」技能，安装后检查 SKILL.md 及 references 文件是否齐全。

安装后，附上视频，有稿也一并附上，然后发：

> 用 $hetu-koubo-edit 剪这段口播。先核对实录，剪掉口误和多余气口，再按句规划并做成片。前三帧全屏露脸，第一句话的重点放在脸侧。复杂内容用图解，适合提问的地方弹回真人。

## 里面有什么

- [剪辑规则](skills/hetu-koubo-edit/SKILL.md)涵盖露脸开场、按词触发、真人让位与弹回、图文美化、字幕、拟音及成片验收。
- [分类动效案例](skills/hetu-koubo-edit/references/motion-cases.md)收录 23 套 MotionGit 模板和 5 个工程。每类说明什么场景适合用、应借哪种动作，并附作者入口。
- 使用时需要可读取的素材和可用的本地剪辑、渲染能力。可用 ChatCut 或其他能处理画面、蒙版、字幕和音轨的工具。安装技能会提供工作方法，模板工程按需获取。

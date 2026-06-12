# fable5-landing-pages

**One model, four tellings.** — Claude Fable 5 landing pages in four design languages.

同一个模型,四种讲法。四个互不相同的 Claude Fable 5 落地页,外加一座「四扇门」入口,全部为零依赖的单文件 HTML(仅引用 Google Fonts)。

## 页面

| 文件 | 版本 | 设计语言 |
|---|---|---|
| [`index.html`](index.html) | 四扇门 · Four Tellings | 入口门廊:四列分屏,悬停展开,键盘 1–4 进门,按 5 命运转门 |
| [`fable.html`](fable.html) | 神话之书 · A Modern Fable | 暗色编辑风:Fraunces 衬线、余烬金、视差星空、自定义光标 |
| [`fable-fieldnotes.html`](fable-fieldnotes.html) | 田野笔记 · Field Notes | 多巴胺新粗野主义:档案纸、贴纸拼贴、硬阴影、原生 CSS scroll-driven 动画 |
| [`fable-bios.html`](fable-bios.html) | FABLE BIOS · The Terminal | 复古未来 CRT:磷光辉光、扫描线、BIOS 开机自检、可交互终端(输入 `help`) |
| [`fable-zen.html`](fable-zen.html) | 寓言 · Ink & Paper | 禅意水墨:宣纸、毛笔字、朱印、起承转结,圆相随阅读进度画满 |

## 运行

无构建步骤。任选其一:

```bash
# 本地静态服务
python3 -m http.server 8743
# 然后访问 http://localhost:8743/

# 或者直接双击 index.html
```

## 彩蛋

每一版都藏了五个彩蛋,提示写在各页页脚的小字里。
找不到的话——每一版的 dev console 里都有一条会全部招供的留言。

## 提示词

> Generate a landing about yourself, Claude Fable 5. You're totally free, but make sure it's visually appealing, clean, interactive, with motion, easter egg's, and scrolling effect. Search and use 2026 design trends

具体设计方向(配色、字体、动效、彩蛋)均由模型自行决定。

## 致谢

提示词出处:[@Aurelien_Gz 的这条 X](https://x.com/Aurelien_Gz/status/2064459148016619928),特此致谢。

设计参考 2026 年 Web 设计趋势:kinetic typography、scrollytelling、
neo-brutalism、dopamine palettes、CSS scroll-driven animations、retrofuturism。

由 Claude Fable 5 自述并编写。✦

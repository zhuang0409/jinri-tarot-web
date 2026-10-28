# 今日塔罗 · Daily Tarot (web)

写下一个梦，或此刻的感受，抽出一张会动的抽象牌。正面是画，翻过来才有牌名和一句话。

Write a dream or a feeling and draw an animated abstract card. The front is a picture only; the words are on the back.

**Live: https://zhuang0409.github.io/jinri-tarot-web/**

- 一个单独的 `index.html`，没有依赖、没有构建步骤。
- 全部在浏览器里生成：不联网，不用任何 AI，你写的话不会离开你的浏览器，也不会被保存。
- 靠一份情绪词表（中文、英文、德文）把你的话对应到 11 张牌：女祭司、倒吊人、恶魔、塔、星星、月亮、太阳、隐者、命运之轮、死神、愚者。词表读得比较粗，没命中任何词时会随机给一张。
- 牌背面的那句话就是你自己写的话。
- 如果文字里出现想伤害自己的词，页面会显示求助提示。这只是一幅画，不能替代真人的陪伴。

One self-contained `index.html`. Everything is drawn on a canvas in your browser; no network calls, no AI, nothing you type leaves the page or is stored. A small word list (Chinese, English, German) maps your text to one of 11 cards. It reads roughly and gives a random card when nothing matches.

Python version of the same cards (renders mp4 loops): see the `ringwork` package in the author's other repository.

Made with a coding agent (Claude Code); the idea and direction are the author's. MIT license.

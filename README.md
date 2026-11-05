[README.md](https://github.com/user-attachments/files/34417536/README.md)
# 纸牌历 / The Solitaire Calendar

一个受乔斯坦·贾德《纸牌的秘密》启发的每日扑克牌日历。

## 关于《纸牌历》 / About the Solitaire Calendar

这副日历的灵感来自乔斯坦·贾德的《纸牌的秘密》。愿你这张没有点数也没有花色的丑角牌，在这个世界上的条条框框之外，永远留着一份好奇、一点荒诞，一身自由。由此掀开你的今日——

Inspired by Jostein Gaarder's *The Solitaire Mystery*. May you be the Joker—the card with no rank and no suit. Beyond the rules and boxes of this world, may there always remain a measure of curiosity, a touch of absurdity, and a freedom all your own. And from there, your today begins—

## 这是什么 / What is this

一个纯前端单文件网页：一年 13 个月、每月 28 天，52 周对应 52 张牌；打开就能看到今天对应的牌面、星期符号、月份和公历日期。

A single-file, pure front-end web page: 13 months of 28 days and 52 weeks mapped to 52 cards. Open it and see today's card, weekday symbol, month, and Gregorian date.

## 怎么用 / How to use

- 在线访问：[GitHub Pages](https://gabriellejao.github.io/solitaire_calendar/)。
- 本地使用：下载 `index.html`，双击用浏览器打开即可。

- Online: [GitHub Pages](https://gabriellejao.github.io/solitaire_calendar/).
- Locally: download `index.html` and open it in any browser.

## 规则简述 / Rules at a glance

- 一年分 13 个月，每月 28 天，共 364 天；月份为一月…十三月。
- 13 个月之后剩 1 天（平年 12/31）或 2 天（闰年 12/30–31），是丑角日，不属任何月份或周。
- 52 周对应 52 张牌，从方块 A 到黑桃 K；每年 1 月 1 日重置为方块 A，每 7 天推进一张牌。
- 52 周分 4 个花色，每个花色 13 周（A→K）：方块 → 梅花 → 红心 → 黑桃。
- 月份与周牌点数相互独立：月份数不等于牌点，二者不必对应。
- 星期符号跟随真实公历星期：周一 ☾ Luna，周二 ♂ Martis，周三 ☿ Mercurii，周四 ♃ Jovis，周五 ♀ Veneris，周六 ♄ Saturni，周日 ☉ Solis。
- 平年 12 月 31 日为彩色丑角日；闰年 12 月 30 日为黑白丑角日，12 月 31 日为彩色丑角日。
- 年份花色四年循环：1984 方块年 → 1985 梅花年 → 1986 红心年 → 1987 黑桃年 → 1988 方块年……；年份花色与周牌花色是两套独立系统。

- A year has 13 months of 28 days (364 days): the 1st Month … the 13th Month.
- After the 13 months, 1 day remains in a common year (Dec 31) or 2 days in a leap year (Dec 30–31); these are Joker days, outside all months and weeks.
- 52 weeks map to 52 cards, from Ace of Diamonds to King of Spades; the sequence resets to Ace of Diamonds on January 1 and advances one card every 7 days.
- The 52 weeks are divided into 4 suits of 13 weeks each (A→K): Diamonds → Clubs → Hearts → Spades.
- Month numbers and card ranks are independent; a month does not necessarily match the card rank.
- The weekday symbol follows the real Gregorian weekday: Mon ☾ Luna, Tue ♂ Martis, Wed ☿ Mercurii, Thu ♃ Jovis, Fri ♀ Veneris, Sat ♄ Saturni, Sun ☉ Solis.
- In a common year, December 31 is the Colorful Joker Day; in a leap year, December 30 is the Black & White Joker Day and December 31 is the Colorful Joker Day.
- The year suit cycles every four years: 1984 Diamonds → 1985 Clubs → 1986 Hearts → 1987 Spades → 1988 Diamonds…; the year suit is independent of the week-card suit.

## 技术 / Tech

- 单文件 HTML + 内联 CSS/JS，零依赖。
- 牌面用 SVG 程序化绘制，不引用外部图片。
- 优先适配手机竖屏。

- Single-file HTML with inline CSS/JS, zero dependencies.
- Card faces are drawn programmatically with SVG; no external images.
- Optimized for mobile portrait screens.

## 协议 / License

MIT License. 见 `LICENSE` 文件。 / See the `LICENSE` file.

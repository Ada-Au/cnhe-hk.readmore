# 《空山印深情・王維》小遊戲

Can be used via iframe or just as a website. send data to parent container.

**聽聲連線(唐朝樂器)(connect)** sendData with tries, the **_lower_** the better \
**配對(唐朝舞蹈)(matching⁠)** sendData with tries, the **_lower_** the better \
**詩畫對對碰(詩佛王維)(pair⁠)** sendData with tries, the **_lower_** the better \
**砌圖(王維畫)(puzzle)** sendData with time, the **_shorter_** the better \
**唐詩(⁠ 聲韻接字)(rhymes)** sendData with marks, the **_higher_** the better \
**過三關(唐玄宗、楊貴妃)⁠(ticTacToe)** sendData with marks, the **_higher_** the better\
\
{type: ["connect" || "matching" || "pair" || "puzzle" || "rhymes" || "ticTacToe], [tries || time || marks]: number}

# 中華儒将：智、仁、勇

Everything is now counted with marks\
{type: ["connect" || "matching" || "pair" || "puzzle" || "rhymes" || "ticTacToe], marks: number}

**connect**\
10\* 連線次數 / 題目總數\
\
**matching**\
10 - 配對次數 / 題目總數 / 2\
\
**pair**\
10 - (配對次數 - 題目總數 \*2) / 題目總數 / 2\
\
**puzzle**\
1 分鐘內: 10
3 分鐘內: 10 - 時間 / 30 秒
3 分鐘以外: 10 - 時間 / 60 秒\
\
**rhymes**\
錯 1 次扣 0.5 分\
\
**ticTacToe**\
最少需要回答的題目總數/勝利時回答的題目總數

## To reduce image size

```sh最少需要回答
imgmini 1.jpg 2.jpg 3.jpg 4.jpg 5.jpg 6.jpg
```

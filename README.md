# 《空山印深情・王維》小遊戲

Can be used via iframe or just as a website. send data to parent container.

**聽聲連線(唐朝樂器)(connect)** postMessage with tries, the **_lower_** the better \
**配對(唐朝舞蹈)(matching⁠)** postMessage with tries, the **_lower_** the better \
**詩畫對對碰(詩佛王維)(pair⁠)** postMessage with tries, the **_lower_** the better \
**砌圖(王維畫)(puzzle)** postMessage with time, the **_shorter_** the better \
**唐詩(聲韻接字)(rhymes)** postMessage with marks, the **_higher_** the better \
**過三關(唐玄宗、楊貴妃)⁠(ticTacToe)** postMessage with marks, the **_higher_** the better\
\
{type: ["connect" || "matching" || "pair" || "puzzle" || "rhymes" || "ticTacToe], [tries || time || marks]: number}

# 中華儒将：智、仁、勇

Everything is now counted with marks\
{type: ["connect" || "matching" || "pair" || "puzzle" || "rhymes" || "ticTacToe], marks: number}

**connect(連線)**\
10\* 題目總數 / 連線次數\
\
**matching(⁠ 配對)**\
10 - 配對次數 / 題目總數 / 2\
\
**pair(⁠ 對對碰)**\
10 - (配對次數 - 題目總數 \*2) / 題目總數 / 2\
\
**puzzle(⁠ 砌圖)**\
1 分鐘內: 10
1-2 分鐘：每多 15 秒，扣 1 分
2 分鐘後：每多 10 秒，扣 1 分
\
**rhymes(⁠ 接字)**\
錯 1 次扣 0.5 分\
\
**ticTacToe(過四關)**\
4 次過關：10 分
每多一次：扣 1 分

## To reduce image size

```sh最少需要回答
imgmini 1.jpg 2.jpg 3.jpg 4.jpg 5.jpg 6.jpg
```

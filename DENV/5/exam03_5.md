# 讀取txt-尋找班上黑馬(Dark Horse) #

## 說明 ##

<b>黑馬(Dark Horse)</b>一詞源於19世紀的英國政治家班傑明·迪斯雷利的小說《年輕的公爵》（The Young Duke，1831）。<br>
該小說有一處對賽馬比賽的描寫，比賽中一匹不起眼的黑馬在最後關頭趕超了兩匹奪冠呼聲最高的良種馬。<br>
黑馬就用來比喻出人意料的獲勝者。<br>

現在我們有某公館國中班上的數學<b>期中考</b>與<b>期末考</b>的成績檔案<br>
請讀取：<br>
1.期中考： <code>../app/MathScoreMid01.txt</code> <br>
2.期末考： <code>../app/MathScoreFinal01.txt</code> <br>
找到期末考進步最多的學生，並列印出來<br>
<br>
ID:學生編號<br>
score:考試成績<br>
<br>
黑馬定義：期末考減去期中考成績進步最多者。<br>
黑馬可能不只一位<br>

## Input Format ##

輸入兩個字串表示下列兩個檔案的名字。例如 MathScoreMid01.txt ， MathScoreFinal01.txt 。<br>
這兩個文字檔的所在位置為<code>../app/MathScoreMid01.txt</code>與<code>../app/MathScoreFinal01.txt</code><br>
1.期中考成績.txt<br>
2.期末考成績.txt<br>

## Output Format ##

Dark Horse: 學生ID (若黑馬不只一位，請用&隔開)<br> 
?.? Points Progress (取到小數點後一位) <br>

## Sample Input 1 ##
```
MathScoreMid01.txt
MathScoreFinal01.txt

```

## Sample Output 1 ##
```
Dark Horse: s18      (非正解)
78.0 Points Progress (非正解)
```

## Sample Input 1 ##
```
MathScoreMid05.txt
MathScoreFinal05.txt

```

## Sample Output 1 ##
```
Dark Horse: s18 & s19 & 20     (非正解)
78.0 Points Progress           (非正解)
```

## Hint ##

```
1.注意空格，若有兩人以上都是黑馬，都要列印出來，並且用&分開。
2.若有兩人以上都是黑馬，要先排序過後再列印出來。
3.輸出最末端沒有空格。

```

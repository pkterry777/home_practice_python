# 文字外殼包裝 #

## 說明 ##

有時候在電腦寫筆記時，會想要用一些符號(如#)把某些特定文字框起來，以便我們以後閱讀。<br>
如：This is an example 我們把它包裝成<br>
<br>
```
####################
#This is an example#
####################
```
<br>
1.今天讓使用者任意輸入多行文字(while迴圈)，並且輸入-1離開輸入。<br>
2.再請使用者輸入想要使用符號(如： # - ! $ @...等等)。<br>
3.把文字包住輸出。<br>
<br>
例如：<br>
Hello, world!<br>
This is an example.<br>
↓↓↓利用*包裝後如下↓↓↓<br>
<br>

```
*********************
*Hello, world!      *
*This is an example.*
*********************
```
<br>

## Input Format ##

字串1(str)<br>
字串2(str)<br>
...<br>
字串n(str)<br>
-1<br>
字串(str)(為符號，如:# ~ ! $ % ^ & * -等符號)<br>

## Output Format ##

假設符號為：%
```
%%%%%%%%%%%%
%字串1(str)%
%字串2(str)%
%...       %
%字串n(str)%
%%%%%%%%%%%%
```
## Sample Input 1 ##
```
Keep Calm and Carry On
-1
#
```

## Sample Output 1 ##
```
########################
#Keep Calm and Carry On#
########################
```
## Sample Input 2 ##
```
When you give up,
that's when the game is over.
-1
^
```

## Sample Output 2 ##
```
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
^When you give up,            ^
^that's when the game is over.^
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
```
## Sample Input 3 ##
```
This night is flawless, don't you let it go
I'm wonderstruck, dancing around all alone
I'll spend forever wondering if you knew
I was enchanted to meet you
-1
@
```

## Sample Output 3 ##
```
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@This night is flawless, don't you let it go@
@I'm wonderstruck, dancing around all alone @
@I'll spend forever wondering if you knew   @
@I was enchanted to meet you                @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
```
## Hint ##

```
1.可利用list先把輸入過的字串儲存起來。
2.尾巴的符號要對齊。
3.輸出的最最最最末端有個換行，如下：
########################
#Keep Calm and Carry On#
########################<--這裡有個換行
```

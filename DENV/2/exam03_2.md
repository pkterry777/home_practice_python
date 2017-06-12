# 輸入數字直到q離開II #

## 說明 ##

輸入數字(int或float)，儲存進一個List容器裡面，直到輸入q後程式結束。<br>
但使用者總是暴力的，所以若使用者輸入的不是數字，則提醒使用者"Please Enter Numbers Only"<br>
最後列印出使用者輸入的數字<br>
1.List容器(未排序過)<br>
2.List容器(由數字小到大排序)<br>
3.List容器(由數字大到小排序)<br>
4.List容器(未排序過)<br>

## Input Format ##

數字1(int 或 float)<br>
數字2(int 或 float)<br>
...<br>
q<br>

## Output Format ##

List容器(未排序過)<br>
List容器(由數字小到大排序)<br>
List容器(由數字大到小排序)<br>
List容器(未排序過)<br>


## Sample Input 1 ##
```
1
2
3
-3
-2
q
```

## Sample Output 1 ##
```
[1, 2, 3, -3, -2]
[-3, -2, 1, 2, 3]
[3, 2, 1, -2, -3]
[1, 2, 3, -3, -2]
```
## Sample Input 2 ##
```
8
5
python (這邊要提醒使用者"Please Enter Numbers Only")
-3
q
```

## Sample Output 2 ##
```
Please Enter Numbers Only
[8, 5, -3]
[-3, 5, 8]
[8, 5, -3]
[8, 5, -3]
```

## Hint ##

```
1.注意Please Enter Numbers Only的大小寫。

```

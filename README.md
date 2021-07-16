# 一.简易成绩管理系统
### 1.创建已知行数未知列数的二维数组
  > String score[][] = new String[classNum][];
  > score[i] = new String[stuNum];
  /n行数不可以未知
### 2.关于nextLine的使用
  > stuNum = input.nextInt();
  > scoreLine = input.nextLine();
	> scoreLine = input.nextLine();
  若nextLine前有其他input.
  此input.nextLine就会接收到“”
  因此要重复一遍input.nextLine
### 3.split对字符串以给定的字符进行分隔，得到字符串数组
  > score[i] = scoreLine.split(" ");
  scoreLine = 11 12 13
  则得到score[o] = 11
        score[1] = 12
        score[2] = 13
### 4.input得到的是String，要进行加减要转换为整数/小数
  > addClass[i] += Integer.parseInt(score[i][a]);

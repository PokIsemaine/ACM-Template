ACM-Template

## 介绍

鱼竿的ACM模板库，借助GitHub辅助多人协作以及版本更新

## 贡献者&感谢名单

| 用户        | 友链                                                         |
| ----------- | ------------------------------------------------------------ |
| PokIsemaine | [CSDN](https://blog.csdn.net/qq_39354847?spm=1001.2014.3001.5343),[GitHub](https://github.com/PokIsemaine) |
|             |                                                              |
|             |                                                              |



## 我要如何参与更新当中

### 前置知识

掌握Github以及Git的基本操作
[学会Git玩转Github【全】](https://www.bilibili.com/video/BV1Xx411m7kn?p=5)

### 代码风格

为了尽可能统一风格

一下几点需要**严格执行**，否则将被驳回

```c++
#include<iostream.h>//
#define MAX_N 100//宏命名统一采用大写（可使用下划线对单词区分）
//头文件，宏预处理与常量变量之间空一行
const int kDaysInAWeek = 7;//常量命名k开头，大小写混合
int array[MAX_N];//数组统一创建在main函数外部
int num;
//常量变量与函数之间空一行
int get_num()//获取某一个值的命名采用get_变量名
{
    return num;
}
bool is_prime()//bool类型采用is_或check_结构
{
    
}
bool check_prime()
{
    
}
//函数与主函数之间空一行
int main()
{
    int ans=0;//main内部的变量必须初始化
    for(int i=1;i<=n;i++)//循环变量必须定义在for内部
    {
        num++;
    }//同一采用换行大括号
    
    ans=get_num()
    printf("%d\n",ans);
    return 0;//必须正确return
}
```

代码命名需要尽可能减少缩写，必须有具体意义(常见用法除外)

常见用法

| 变量缩写         | 说明                     | 含义                         |
| ---------------- | ------------------------ | ---------------------------- |
| T                |                          | 多组输入                     |
| C                |                          | Case                         |
| i，j , k         |                          | 循环（依次嵌套使用）         |
| l,r,mid,be,en,st | st=start,be=begin,en=end | 左，右，中，起点，重点，开始 |
| p                | prime/power              | 素数,幂                      |
| phi,eulers       |                          | 欧拉函数                     |
| gcd,lcm          |                          | 最大公约数，最小公倍数       |
| cnt              | count                    | 计数                         |
| add,sub,mul,div  | div=divison              | 加减乘除                     |
| vis,flag         |                          | 标记                         |
| b                | base                     | 底数                         |
| inf              | infinite                 | 无穷                         |
| r                |                          | 余数                         |
| odd,even         |                          | 奇数偶数                     |
| divisors         |                          | 约数                         |
| divide           |                          | 质因数分解                   |
| maxi,mini        |                          | 最大值位置，最小值位置       |
| Q                | query                    | 查询                         |
| init             |                          | 初始化                       |


#include<stdio.h>
void main()
{
  int abc,x,y,z;
  printf("请输入一个整数:\n");
  scanf("%d",abc);
  printf("交换前abc=%d",abc);
  x=abc/100;
  y=(abc-x)/10;
  z=(abc-x-y);
  printf("交换后x=%d,y=%d,z=%d\n",x,y,z);

# sec220
#include<stdio.h>
enum days{sun,mon=5,tue,wed,thu,fri};
enum prices{d1=10,d2,d3,d4,d5=5};
int main(){
int applecost=sun+d1;
int bananacost=wed+d3;
printf("apple costs on day1:%d\n:",applecost);
printf("banana costs on day3:%d\n",bananacost);
}

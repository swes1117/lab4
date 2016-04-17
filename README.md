questionA:
如果你想將你第一個函示 double average(double *,double &);為可執行的話，你必須先定義例如以下:
double *a=x;
x=3.5;
double &b=y;
y=3.5;
average(a,b);(結果是(3.5+3.5)/2)
證明如果要使其函示成立需先用兩個變數x,y來儲存其值，即可。
第二個函示使用方法就一般給定兩個邊數(一個為整數變數一個為浮點變數)即可。
questionB:
由OUTPUT可知，在vim的環境下，char是1byte,int是4bytes,float也是4bytes,double則是8bytes，然而在指標變數中所有型態皆是8bytes。
結果如下:
1 8
4 8
4 8
8 8

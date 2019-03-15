``` c
int *p1,*p2,*p3, num = 45;

//P1 apunta a num
p1 = &num;

p2=p1;
p3=p2;

//Se modifica P1
p1=p3;

```

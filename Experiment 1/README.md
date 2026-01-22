## Experiment 1

## Experiment 1A

## TITLE: Display the primitive datatypes

---

## SOURCE CODE: primitive datatypes

```

public class task1a {
byte b;
int i;
double dou;
boolean bo;
char c;
float f;
long l;
short s;
public static void main(String[] args){
task1a t=new task1a();
System.out.println("default value of byte is:"+t.b);
System.out.println("default value of int is:"+t.i);
System.out.println("default value of double is:"+t.dou);
System.out.println("def val of boolean is:"+t.bo);
System.out.println("def val of char is:"+t.c);
System.out.println("def val of float is:"+t.f);
System.out.println("def val of long is:"+t.l);
System.out.println("def val of short is:"+t.s);
}
}
```
## output
<img width="476" height="496" alt="Screenshot 2026-01-21 205945" src="https://github.com/user-attachments/assets/03060543-31f5-4c1a-87ad-21b8817d2b0f" />



## EXPERIMENT 1B

## TITLE: Display the Quadratic Equations

---

## SOURCE CODE: Quadratic Equations

```
import java.util.Scanner;
public class quad
{
public static void main(String[] args) {
Scanner s=new Scanner(System.in);
System.out.println("enter coeff of a:");
double a=s.nextDouble();
System.out.println("enter coeff of b:");
double b=s.nextDouble();
System.out.println("enter coeff of c:");
double c=s.nextDouble();
double discriminant=b*b-4*a*c;
if(discriminant>0)
{
double root1=(-b+Math.sqrt(discriminant))/(2*a);
double root2=(-b-Math.sqrt(discriminant))/(2*a);
System.out.println("the roots are real and distinct");
System.out.println("root1:"+root1);
System.out.println("root2:"+root2);
}
else if(discriminant==0)
{
double root=-b/(2*a);
System.out.println("the root is real and equal");
System.out.println("root:"+root);
}
else
{
double realpart=-b/(2*a);
double imaginarypary=Math.sqrt(-discriminant)/(2*a);
System.out.println("the roots are complex and distinct");
System.out.println("root1:" + realpart + "+" + imaginarypart + "i");
System.out.println("root2:" + realpart + "-" + imaginarypart + "i");
}
}
}
```


## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2025-12-20 154240" src="https://github.com/user-attachments/assets/331bc3a9-e8ea-4f80-b5fb-fd4bce7f7edb" />



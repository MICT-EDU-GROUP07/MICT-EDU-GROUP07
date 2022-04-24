#include<stdio.h>
int add( int, int);
int substract(int, int);
int diff( int, int);
int main() {
int a,b;
printf("enter value of a\n");
scanf("%d",&a);
printf("enter value of b\n");
scanf("%d",&b);
printf("add=%d\n",add(a, b));
printf("substract=%d\n",substract(a, b));
printf("diff=%d\n",diff(a, b));
return 0;
}
int add(int c, int f){
int sum;
sum=c+f;
return sum;
}
int substract(int g, int h){
int kutoa;
kutoa=g-h;
return kutoa;
} 
int diff(int p, int q){
int tofauti;
tofauti=p-q;
return tofauti;
}

The brief description on four pillars of java is applicable in  the existing c-programming function-source code.
Abstraction; this is used to hide the implementation and always show only functionality to the user.
	In the c-program above the abstraction is applied in the main function when the function source code
 	ask the user to enter the value of "a" and "b"..
Inheritance; this process involves creation of new class that is inherited by another class in java programming language.
	In above c-progamming function-source code, the inheritance takes place on the function definition from function
	declared as add(),substract() and diff().
Encapsulation; this pillar wraps the code and data into one unit and be better for unit testing since it hides data.
	The function above combines three function such as add(),substract() and diff() in a single unit code which performs all operation.
Polymorphism; this means a function can have many forms of explaining the required code for obtaining the same solution.
	This is often used in other languages other than c-programming language like java and others.

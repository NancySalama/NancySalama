/*Aufgabe hs_4
#include <stdio.h>
int main(void)
{
	int a;
	int b;
	int c;
	scanf("%i",&a);
	scanf("%i",&b);
	//a=1;
	//b=2;
	c=a*b;
	printf("Das Produkt von a und b ist %d!",c);
	return 0;
}

/*hs_5.c
#include <stdio.h>
int main(void){
              int c;
              c=sizeof(char);
              printf("Size of Char is %i\n",c);
              int i;
              c=sizeof(int);
              printf("Size of int is %i\n",i);
              int l;
              c=sizeof(long);
              printf("Size of long is %i\n",l);
              int f;
              c=sizeof(double);
              printf("Size of double is %i\n",f);
	
}

/*hs_51
#include<stdio.h>
int main(){
          int a,b; 
	        float c;
	float d;
	a = 1234567890;
	c = a;
	b = c;
  int z=a-b;
	d = 0.4;
	printf("\Value of a is %d\n",a);
	printf("\Value of a is %d\n",b);
	printf("\Value of a is %f\n",c);
  printf("\Value of a is %d\n",z);
  printf("\Value of a is %12f\n",f);
}
/*hs_6
#include <stdio.h>
#include <math.h>
int main(void){
            double a;
            double b;
            int jahr;
            scanf("%lf",&a);
            scanf("%lf",&b);
            b=b/100;
            scanf("%d",&jahr);
            double interest;
            for (int i =0;i<jahr;i++){
                                        interest = a*(1+(b*jahr));
                                        printf("%lf",interest);
            
            }
}
/*hs_7

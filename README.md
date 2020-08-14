#include<stdio.h>

int main() {
  
      int x;
      printf("Enter a Number(1,2,3,4,5):");
      scanf("%d", & x);
     
      switch(x) {
            case 1:
                 printf("Food Item-Pizza\n Price-Rs. 239\n");
                 break;
            case 2:
                 printf("Food Item-Burger\n Price-Rs. 129\n");
                 break;
            case 3:
                 printf("Food Item-Pasta\n Price-Rs. 179\n");
                 break;
            case 4:
                 printf("Food Item-French Fries\n Price-Rs. 99\n");
                 break;
            case 5:
                 printf("Food Item-Sandwich\n Price-Rs. 149\n");
                 break;
            }
        return 0;
  }

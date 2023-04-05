#define _CRT_SECURE_NO_WARNINGS 
#include<stdio.h>


int main() {

   int S, K, H;
   scanf_s("%d\n %d\n %d", &S, &K, &H);
   
   int total = S + K + H;
   
   if (total >= 100) {
   
      printf("OK");
   }
   else if ((K > S) && (H > S)) {
   
      printf("Soongsil");
   }
   else if ((S > K) && (H > K)) {
   
      printf("Korea");
   }
   else{
   
      printf("Hanyang");
   }
   return 0;
}

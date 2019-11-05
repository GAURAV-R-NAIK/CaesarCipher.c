# CaesarCipher.c
/*Caesar Cipher using C programming*/

#include<stdio.h>
#include<string.h>
void main()
{
     
     int i;
     char password[40]; 
     printf("Enter a Password:\t");
     scanf("%s", password);
      for(i = 0; i < strlen(password); i++)
      {
            password[i] = password[i] + 3;
      }
      printf("\nEncrypted Password:%s\n", password);
      for(i = 0; i < strlen(password); i++)
      {
            password[i] = password[i] - 3;
      }
      printf("\nDecrypted Password:%s\n", password);
      
}

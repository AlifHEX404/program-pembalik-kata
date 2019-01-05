# program-pembalik-kata


          #include <stdio.h>
          #include <string.h>
          #include <conio.h>

          char a [100];
          int b,c;
          int main ()
          {  balik:
              printf(" \t|=======================================================|\n");
          printf(" \t|======= PROGRAM PEMBALIK KATA ATAU KALIMAT ============|\n") ;
          printf(" \t|=================== ALIF MUSTAFANAH ===================|\n") ;
          printf(" \t|=======================================================|\n");
          printf(" \t\n");
              printf( " Masukan Kata / Kalimat :");
              gets(a);
              printf(" \t\n");
              strrev(a);
              printf( " Di Balik Menjadi :%s",a);
              printf(" \t\n");
              printf(" \t\n");
              goto balik;
          }

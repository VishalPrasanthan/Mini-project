#include<stdio.h> 
#include<conio.h> 
Void main() 
{ 
int ch,qty,tot; 
Clrscr(); 
Printf(“\n\tMenu card”); 
Printf (“\n\t\t1.cofee                              Rs:15”); 
Printf(“\n\t\t2.Tea                                   Rs:10”); 
Printf(“\n\t\t3.Idly                                   Rs:25”); 
Printf(“\n\t\t4.Dosa                                 Rs:50”); 
Printf(“\n\nEnter ur choice        :”); 
Scanf(“%d”,&ch); 
Switch(ch) 
{ 
Case 1: 
    Printf(“\nyou have selected cofee”); 
    Printf(“\nEnter the qty:”); 
    Scanf(“%d”,&qty); 
    Printf(“\nTotal amount :%d”,(qty*15));  
   break; 
Case 2: 
   Printf(“\nyou have selected tea”); 
   Printf(“\nEnter the qty:”); 
   Scanf(“%d”,&qty); 
   Printf(“\nTotal amount :%d”,(qty*10)); 
   break;   
Case 3: 
  Printf(“\nyou have selected Idly”); 
  Printf(“\nEnter the qty:”); 
  Scanf(“%d”,&qty); 
  Printf(“\nTotal amount :%d”,(qty*25)); 
  break; 
Case 4: 
 Printf(“\nyou have selected Dosa”); 
 Printf(“\nEnter the qty:”); 
 Scanf(“%d”,&qty); 
 Printf(“\nTotal amount :%d”,(qty*50)); 
break; 
Default: 
 Printf(“\nInvalid product selected”); 
 break; 
} 
getch(); 
} 

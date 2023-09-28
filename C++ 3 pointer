#include <bits/stdc++.h> 
void sort012(int *arr, int n)
{
   int i=0, j=n-1;
   int k=0;
   while(i<j)
   {
      while(arr[i]==0)
      {
         i++;
      }

      while(arr[j]==2)
      {
         j--;
      }

      if(arr[i]==2 && i<j )
      {
         int temp=arr[j];
         arr[j]=arr[i];
         arr[i]=temp;
         j--;
      }

      if(arr[j]==0 && i<j && arr[i]!=0)
      {
         int temp=arr[j];
         arr[j]=arr[i];
         arr[i]=temp;
         i++;
      }
        

      if(arr[i]==1 && arr[j]==1 && i<j)
      {
         k=i;
         while(arr[k]==1)
         {
            k++;
         }      

         if(k<j)
         {
            int temp=arr[k];
            arr[k]=arr[i];
            arr[i]=temp;
         } 

         else
         break;  
      }
            
   }
}

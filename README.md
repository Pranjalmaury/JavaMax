# JavaMax

import java.io.*;
import java. lang.*;
import java. util.*;

class test{

public static int Max12(int arr[],int n){

   int max= Integer.MIN_VALUE;

   for(int i=0;i<n;i++){

   if(max < arr[i]){

   max=arr[i];
   }
   
   }

   return max;
   
}
}


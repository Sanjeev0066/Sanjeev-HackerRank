# Sanjeev-HackerRank
Java programs
import java.io.*;
import java.util.*;

public class Solution {

       public static void main(String[] args) {
       Scanner scan = new Scanner(System.in);
       
       int q=scan.nextInt();
          
          for( int i=1; i<=q;i++)
          {
                int a=scan.nextInt();
                int b=scan.nextInt();
                int n=scan.nextInt(); 
                              
                int sum=a;
                
                
                         for(int k=0;k<n;k++)
                         {
                      
                             sum+=(int)(Math.pow(2, k))*b;
              
                          
               
               
                             System.out.print(sum);
                         
                             System.out.print(' ');
               
                          }           
              System.out.println();
           }
}
}

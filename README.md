# FibonacciNumbers https://Fibonacci-C.alexivashko.repl.run
using System;  
  public class FibonacciExample  
   {  
     public static void Main(string[] args)  
      {  
         int n1=0,n2=1,n3,i,number;    
         Console.Write("Ludzu ievadiet cipari: ");    
         number = int.Parse(Console.ReadLine());  
         Console.Write(n1+" "+n2+" "); //paradis 0 un 1    
         for(i=2;i<number;++i) //loop iesakas no 2 tapec ka 0 un 1 jau radas    
         {    
          n3=n1+n2;    
          Console.Write(n3+" ");    
          n1=n2;    
          n2=n3;    
         }    
      }  
   }  

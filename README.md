# .net example program
 **************
 11.FibonacciExample<br>
 ************
using System;<br>
public class FibonacciExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n1 = 0, n2 = 1, n3, i, number;<br>
        Console.Write("Enter the number of elements: ");<br>
        number = int.Parse(Console.ReadLine());<br>
        Console.Write(n1 + " " + n2 + " "); //printing 0 and 1    <br>
        for (i = 2; i < number; ++i) //loop starts from 2 because 0 and 1 are already printed    <br><br><br>
        {<br>
            n3 = n1 + n2;<br><br>
            Console.Write(n3 + " ");<br>
            n1 = n2;<br>
            n2 = n3;<br><br>
        }<br>
    }<br>
}<br>
 
 Output:<br>
 *********<br>
 ![Screenshot (28)](https://user-images.githubusercontent.com/97940277/155659464-49587883-cf56-4664-b414-03e21626deac.png)<br>
 ***************
 12.Write a C# program to check prime numbers<br>
 *************
 using System;  <br>
  public class PrimeNumberExample  <br>
   {  <br>
     public static void Main(string[] args)  <br>
      {  <br>
          int n, i, m=0, flag=0;    <br>
          Console.Write("Enter the Number to check Prime: ");    <br>
          n = int.Parse(Console.ReadLine());  <br>
          m=n/2;   <br> 
          for(i = 2; i <= m; i++)    <br>
          {    <br><br>
           if(n % i == 0)    <br>
            {    <br>
             Console.Write("Number is not Prime.");    <br>
             flag=1;    <br>
             break;    <br>
            }    <br>
          }    <br>
          if (flag==0)    <br>
           Console.Write("Number is Prime.");   <br>    
     }  <br>
   }  <br>
 Output:<br>
 *********
 ![Screenshot (31)](https://user-images.githubusercontent.com/97940277/155660113-a46bbce0-b6cf-47af-bc35-8d2e318006a1.png)<br>
 ![Screenshot (32)](https://user-images.githubusercontent.com/97940277/155660237-cc79a25c-08b1-4389-9546-402f406d5dba.png)<br>
****************************
 13.Write a C# program to check palindrome number<br>
 *****************************
 using System;  <br>
  public class PalindromeExample  <br>
   {  <br>
     public static void Main(string[] args)  <br>
      {  <br><br>
          int n,r,sum=0,temp;   <br> 
          Console.Write("Enter the Number: ");   <br>
          n = int.Parse(Console.ReadLine());  <br>
          temp=n;  <br>
          while(n>0)<br>
          { <br>
           r=n%10;<br>
           sum=(sum*10)+r; <br>   
           n=n/10; <br>
          } <br>     
          if(temp==sum) <br>     
           Console.Write("Number is Palindrome.");  <br>    
          else      <br>
           Console.Write("Number is not Palindrome");   <br>  
    }  <br>
  }  <br>
Output:<br>
 ![Screenshot (47)](https://user-images.githubusercontent.com/97940277/156499661-a3b106d6-c3ae-489d-b386-4111747b6985.png)<br>
 ![Screenshot (48)](https://user-images.githubusercontent.com/97940277/156499692-3b2488e1-b9af-4377-b8db-0bc30940f56e.png)<br>
*****************************
 14.Write a C# program to check factorial of a number<br>
 ****************************
 using System;<br>
public class FactorialExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int i, fact = 1, number;<br>
        Console.Write("Enter any Number: ");<br>
        number = int.Parse(Console.ReadLine());<br>
        for (i = 1; i <= number; i++)<br>
        {<br>
            fact = fact * i;<br>
        }<br>
        Console.Write("Factorial of " + number + " is: " + fact)<br>
    }<br>
}<br>
 
 Output:<br>
 **********<br>
 ![Screenshot (50)](https://user-images.githubusercontent.com/97940277/156500547-80ae57bf-afcd-4cff-a84d-ef8b562f0b0e.png) <br>

 
 *******************
 15.Write a C# program to check amstrong number.<br>
 *******************
 using System;<br>
public class ArmstrongExample<br>
{<br>
    public static void Main(string[] args)<br>
    {
        int n, r, sum = 0, temp;<br>
        Console.Write("Enter the Number= ");<br>
        n = int.Parse(Console.ReadLine());<br>
        temp = n;<br>
        while (n > 0)<br>
        {<br>
            r = n % 10;<br>
            sum = sum + (r * r * r);<br>
            n = n / 10;<br>
        }<br>
        if (temp == sum)<br>
            Console.Write("Armstrong Number.");<br>
        else<br>
            Console.Write("Not Armstrong Number.");<br>
    }<br>
}<br>
 Output:<br>
 **********<br>
 ![Screenshot (53)](https://user-images.githubusercontent.com/97940277/156501614-412927f2-e375-416d-b9e2-97f49d9e266a.png)<br>
 ![Screenshot (54)](https://user-images.githubusercontent.com/97940277/156501695-e572450f-21a6-4b97-86d2-3037f5afd2a1.png)<br>
 
 *************************
 16.Write a C# program to print sum of digits.<br>
 *************************
 using System;<br>
public class SumExample<br><br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n, sum = 0, m;<br>
        Console.Write("Enter a number: ");<br>
        n = int.Parse(Console.ReadLine());<br>
        while (n > 0)<br>
        {<br>
            m = n % 10;<br>
            sum = sum + m;<br>
            n = n / 10;<br>
        }<br>
        Console.Write("Sum is= " + sum);<br>
    }<br>
}<br>
Output:<br>
********<br>
![Screenshot (57)](https://user-images.githubusercontent.com/97940277/156502543-0c72cb74-ef78-4872-946c-8a3ad5513fb2.png)<br>
![Screenshot (58)](https://user-images.githubusercontent.com/97940277/156502728-04d03e1d-7c05-472d-a81f-74c1ba17ee6d.png)<br>
 
 ********************************
 17.Write a C# program to reverse given number.<br>
 *********************************
 using System;  <br>
  public class ReverseExample  <br>
   {  <br>
     public static void Main(string[] args)  <br>
      {  <br>
       int  n, reverse=0, rem;         <br>  
       Console.Write("Enter a number: ");   <br>   
       n= int.Parse(Console.ReadLine());  <br>   
       while(n!=0)      <br>
       { <br>     
        rem=n%10;  <br>      
        reverse=reverse*10+rem;    <br>  
        n/=10;  <br>    
       }      <br>
       Console.Write("Reversed Number: "+reverse);<br>       
    }  <br>
  }  <br>
 Output:<br>
 *******<br>
![Screenshot (60)](https://user-images.githubusercontent.com/97940277/156503477-26e1a5eb-8c35-4a06-ad35-1e52b0d5e646.png)<br>
 
 ****************************************
 18.Swap two numbers without using third variable.<br>
 **********************************
using System;<br>
public class SwapExample<br>
{<br>
    public static void Main(string[] args)<br><br><br>
    {<br>
        int a = 5, b = 10;<br>
        Console.WriteLine("Before swap a= " + a + " b= " + b);<br>
        a = a * b; //a=50 (5*10)  <br>    
        b = a / b; //b=5 (50/10)      <br>
        a = a / b; //a=10 (50/5)  <br>  
        Console.Write("After swap a= " + a + " b= " + b);<br>
    }<br>
}<br>
 Output:<br>
 *******<br>
 ![Screenshot (62)](https://user-images.githubusercontent.com/97940277/156504154-2d664af7-5704-4539-8881-3d6a2d1e2bb7.png)<br>
 
 *********************************************
 19.Write a C# program to convert decimal number to binary<br>
 **********************************************
 using System;<br>
public class ConversionExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n, i;<br>
        int[] a = new int[10];<br>
        Console.Write("Enter the number to convert: ");<br>
        n = int.Parse(Console.ReadLine());<br><br>
        for (i = 0; n > 0; i++)<br>
        {<br>
            a[i] = n % 2;<br>
            n = n / 2;<br>
        }<br>
        Console.Write("Binary of the given number= ");<br>
        for (i = i - 1; i >= 0; i--)<br>
        {<br>
            Console.Write(a[i]);<br>
        }<br>
    }<br>
}<br>
 Output:<br>
 *******<br>
 ![Screenshot (65)](https://user-images.githubusercontent.com/97940277/156504761-2efc81a1-0b70-4232-8833-cfe10dff9a82.png)<br>
 ![Screenshot (65)](https://user-images.githubusercontent.com/97940277/156504882-23f46e07-d7ee-4389-aa54-1dd712de1d41.png)<br>
 
 ********************************
 20.Write a C# program to print alphabet triangle<br>
 *******************************
 using System;<br>
public class PrintExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        char ch = 'A';<br>
        int i, j, k, m;<br>
        for (i = 1; i <= 5; i++)<br>
        {<br>
            for (j = 5; j >= i; j--)<br>
                Console.Write(" ");<br>
            for (k = 1; k <= i; k++)<br>
                Console.Write(ch++);<br>
            ch--;<br>
            for (m = 1; m < i; m++)<br>
                Console.Write(--ch);<br>
            Console.Write("\n");<br>
            ch = 'A';<br>
        }<br>
    }<br>
}<br>
Output:<br>
********<br>
 ![Screenshot (69)](https://user-images.githubusercontent.com/97940277/156505526-700e4c0a-af66-43b0-a00a-2e25ce60b990.png)<br>

 *****************************
 21.Write a C# program to print number in triangle.<br>
 *****************************
 using System;<br>
public class PrintExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int i, j, k, l, n;<br>
        Console.Write("Enter the Range=");<br>
        n = int.Parse(Console.ReadLine());<br>
        for (i = 1; i <= n; i++)<br>
        {<br>
            for (j = 1; j <= n - i; j++)<br>
            {<br>
                Console.Write(" ");<br>
            }<br>
            for (k = 1; k <= i; k++)<br>
            {<br>
                Console.Write(k);<br>
            }<br>
            for (l = i - 1; l >= 1; l--)<br>
            {<br>
                Console.Write(l);<br><br>
            }<br>
            Console.Write("\n");<br>
        }<br>
    }<br>
}<br>
Output:<br>
********
![Screenshot (71)](https://user-images.githubusercontent.com/97940277/156506272-3b016e00-ec10-43ff-b0b2-e0ab76da96f0.png)<br>
 
*************************************
22. Write a C# program to generate fibonacci triangle.<br>
*************************************
 using System;<br>
public class PrintExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int a = 0, b = 1, i, c, n, j;<br>
        Console.Write("Enter the limit: ");<br>
        n = int.Parse(Console.ReadLine());<br>
        for (i = 1; i <= n; i++)<br>
        {<br>
            a = 0;<br>
            b = 1;<br>
            Console.Write(b + "\t");<br>
            for (j = 1; j < i; j++)<br>
            {<br>
                c = a + b;<br>
                Console.Write(c + "\t");<br>
                a = b;<br>
                b = c;<br>
            }<br>
            Console.Write("\n");<br>
        }<br>
    }<br>
}<br>
Output:<br>
*******<br>
![Screenshot (73)](https://user-images.githubusercontent.com/97940277/156507016-4ebb0e50-2ee8-4353-b005-f2b323d41d81.png)<br>
 
***********************************
23.Write a C# program to convert number in characters.<br>
***********************************
using System;<br>
public class ConversionExample<br>
{<br>v
    public static void Main(string[] args)<br>
    {<br>
        int n, sum = 0, r;<br>
        Console.Write("Enter the Number= ");<br>
        n = int.Parse(Console.ReadLine());<br>
        while (n > 0)<br>
        {<br>
            r = n % 10;<br>
            sum = sum * 10 + r;<br>
            n = n / 10;<br>
        }<br>
        n = sum;<br>
        while (n > 0)<br>
        {<br>
            r = n % 10;<br>
            switch (r)<br>
            {<br>
                case 1:<br>
                    Console.Write("one ");<br>
                    break;<br>
                case 2:<br>
                    Console.Write("two ");<br>
                    break;<br>
                case 3:<br>
                    Console.Write("three ");<br>
                    break;<br>
                case 4:<br>
                    Console.Write("four ");<br>
                    break;<br>
                case 5:<br>
                    Console.Write("five ");<br>
                    break;<br>
                case 6:<br>
                    Console.Write("six ");<br>
                    break;<br>
                case 7:<br>
                    Console.Write("seven ");<br>
                    break;<br>
                case 8:<br>
                    Console.Write("eight ");<br>
                    break;<br>
                case 9:<br>
                    Console.Write("nine ");<br>
                    break;<br>
                case 0:<br>
                    Console.Write("zero ");<br>
                    break;<br>
                default:<br>
                    Console.Write("tttt ");<br>
                    break;<br>
            }//end of switch   <br>   
            n = n / 10;<br>
        }//end of while loop <br>      
    }
}<br>
 
Output:<br>
********<br>
![Screenshot (75)](https://user-images.githubusercontent.com/97940277/156507775-daf6c560-86a4-4d29-921d-b115a553c04e.png)<br>



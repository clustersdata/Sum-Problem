# Sum-Problem

Sum Problem

Problem Description

Hey, welcome to HDOJ(Hangzhou Dianzi University Online Judge).


In this problem, your task is to calculate SUM(n) = 1 + 2 + 3 + ... + n.
 

Input

The input will consist of a series of integers n, one integer per line.
 
Output

For each case, output SUM(n) in one line, followed by a blank line. You may assume the result will be in the range of 32-bit signed integer. 

Sample Input

1
100

Sample Output

1

5050 

解答：

#include<stdio.h>

main()

{

    int n,i,sum;
    
    sum=0;
    
    while((scanf("%d",&n)!=-1))
    
    {
    
        sum=0;
        
        for(i=0;i<=n;i++)
        

            sum+=i;


    printf("%d\n\n",sum);
    
    }
    
    
}


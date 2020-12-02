# C-cp
solutions by me of competitive coding

question:- Input Format

Input will contain four integers -

, one per line.

Output Format

Return the greatest of the four integers.
PS: I/O will be automatically handled.

Sample Input

3
4
6
5

Sample Output

6

solution :- 
#include <iostream>
#include <cstdio>
using namespace std;

void max_of_four()
{
    int a,b,c,d;
    scanf("%d %d %d %d", &a, &b, &c, &d);
    if(a>b&&a>c&&a>d)
    printf("%d",a);
    if(b>a&&b>c&&b>d)
    printf("%d",b);
    if(c>a&&c>b&&c>d)
    printf("%d",c);
    if(d>a&&d>b&&d>c)
    printf("%d",d);
    
}

int main()
{
    max_of_four();
    
    return 0;
}


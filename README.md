# gitty2
this is my second github upload! 
/*To find the sum of series 1!+2!+3!+4!......to n terms*/
#include<iostream.h>
int main()
{
int fact=1, sum=0, n;
cout<<"Enter the number of terms\n";
cin>>n;
for(int i=1;i<=n;i++)
{
	fact=fact*i;
	sum=sum+fact;
}
cout<<"Sum of the series is\n";
cout<<sum;
return 0;
}

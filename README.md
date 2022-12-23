#include<iostream>
#include<cmath>
using namespace std;
int sum(int a,int b)
{
	return a+b;
}
int sub(int a,int b)
{
	return a-b;
}
int mul(int a,int b)
{
	return a*b;
}
int square(int a)
{	
	return a*a;
}
int sq(int b)
{	
	return b*b;
}
float div(float a,float b)
{
	return a/b;
}
int reminder(int a,int b)
{
	return a%b;
}
int lgy(int a,int b)
{	
	cout<<"Log of a is : "<<endl;
	cout<<log(a)<<endl;
	cout<<"Log of b is : "<<endl;
	cout<<log(b);
}

int main( ){
	int a,b,add,diff,pro,dou,dou2,rem,lg;
	float half;
	cout<<"Enter the first integer : ";
	cin>>a;
	cout<<"Enter the second integer : ";
	cin>>b;
	cout<<"The Sum Of Two Integers is :";
	add=sum(a,b);
	cout<<add<<endl;
	cout<<"The Subtraction Of Two Integers is :";
	diff=sub(a,b);
	cout<<diff<<endl;		
	cout<<"The multiplication Of Two Integers is :";	
	pro=mul(a,b);
	cout<<pro<<endl;
	cout<<"The square Of First Integers is :";
	dou=square(a);
	cout<<dou<<endl;
	cout<<"The square Of Second Integers is :";
	dou2=sq(b);
	cout<<dou2<<endl;
	cout<<"The divsion Of two Integers is :";
	half=div(a,b);
	cout<<half<<endl;
	cout<<"The Remainder Of Two Integers is :";
	rem=reminder(a,b);
	cout<<rem<<endl;
	lg=lgy(a,b);
	cout<<lg<<endl;
	
		
		
		
		
}

#include<iostream>
#include<conio.h>
#include<iomanip>

using namespace std;

int main()
{
    float num1,num2;


    cout<<"enter 2 number : ";
    cin>>num1>>num2;
   cout<<showpoint;
   cout<<fixed;
   cout<<setprecision(2);

    float sum = num1+num2;
    cout<<setw(20)<<"sum is: " <<sum;
    cout<<endl;

   //cout<<noshowpoint;
    float sub = num1-num2;
    cout<<setw(20)<<" substraction is: " <<sub;
    cout<<endl;

    float mul = num1*num2;
    cout<<setw(20)<<" multiplication is: " <<mul;
    cout<<endl;



    float divi = num1/num2;
    cout<<setw(20)<<" division is: " <<divi;
    cout<<endl;



    //int rem = num1%num2;
    //cout<<" remaider is: " <<rem;

getch ();
}

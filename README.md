# Factors-of-a-number

#include <iostream.h>

#include <iomanip.h>

#include <conio.h>

 

using namespace std;

 

int main()

{

    int n,i;

    cout<<"Enter a number"<<endl;

    cin>>n;

    cout<<"Factors of"<<n<<"are"<<endl;

    for(i=2;i<=n;i++)

    {

        if(n%i==0)

            cout<<i<<endl;

    }

    getch();

    return 0;

}

 


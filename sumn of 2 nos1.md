# Printing sum of 2 hardcoded numbers using linux using C++ language
## commands used
* Touch hello.cpp-> Creates cpp file
* vi hello.cpp-> Enters insert mode
* g++ hello.cpp->Compiles file and generates output
* ./a.out-> Displays result

## Code:-
#include <iostream>

using namespace std;

int main()
{
   int a,b,c;
   cout<<"enter values of a and b"<<endl;
   cin>>a>>b;
  c=a+b;
   cout<<"sum of a and b = "<<c<<endl;
}

* int creates memory blocks for a,b,c
* cin>> is used to enter values of a and b
* then sum of a nd b is stored in c 
* cout<< is used to print result
![](https://github.com/Divyesh-Kambli/pics/blob/master/sum%20of%202%20nos1.png)
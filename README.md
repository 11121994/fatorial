
#include<iostream>
using namespace std;

long fatorial (long a)

{

	if(a>1)
	return  (a*fatorial(a-1));
	else
	return 1;
	
}



int main()


{
	long numero = 9;
	
	cout << numero<<"!="<<fatorial(numero);
	
	return 0;
	
}

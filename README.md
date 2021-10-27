# Remain-positive
[ display the numbers from 20 to 0 ]
#include<iostream>
using namespace std;
int main()
{
	int myNum = 20;    //declaring variables with datatype int
	while (myNum > 0)   //using while loop
	{
		cout << myNum << endl;   
		myNum=myNum - 0.5;   
	}
	return 0;
}

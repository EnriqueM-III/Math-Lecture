# Math-Lecture

    #include <iostream>
    #include <math.h>
    using namespace std;



	int main()
	{



	cout << "The cube of 8 is " << pow(8, 3) << endl; //pow(num, exponent value)

	cout << "The square root of 8 is " << sqrt(8) << endl; 
	cout << "The square root of 8 is " << pow(8, 1/2) << endl; //pow(num, exponent value)

	cout << "The cube root of 8 is " << cbrt(8) << endl; 
	cout << "The cube root of 8 is " << pow(8, 1/3) << endl; //pow(num, exponent value)
	cout << "////////////////////////////" << endl;



	}

## Input


	#include <iostream>
	#include <math.h>
	using namespace std;



	int main ()
	{

	int x;
	cout << "Your turn! Input a number to determine both cube and square root" << endl;

	do {
		cin >> x;
		if (cin.fail())
			cout << "Not a number " << endl;

	} while (!cin.fail());
	cout << "The square root of " << x << " is " << sqrt(x) << endl;
	cout << "The cube root of " << x << " is " << cbrt(x) << endl;
  
  	}
	

# Lesson-14-extension
// Lesson 14 (extension).cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <math.h>
using namespace std;

int main()
{
	{
		cout << "The cube of 8 is " << pow(8, 3) << endl;
		cout << "The square-root of 8 is " << pow(8, 1 / 2) << endl;
		cout << "The cube-root of 8 is " << cbrt(8) << endl;
		cout << "The cube-root of 8 is " << pow(8, 1 / 3) << endl;
	}
	cout << "This code is an exercise:\n";
	{
		cout << "Please type a number:";
		int input;
		cin >> input;
		cout << " is power of " << pow(input, 3) << endl;
		cout << " is power of " << cbrt(input) << endl;
	}

}

// Run program: Ctrl + F5 or Debug > Start Without Debugging menu
// Debug program: F5 or Debug > Start Debugging menu

// Tips for Getting Started: 
//   1. Use the Solution Explorer window to add/manage files
//   2. Use the Team Explorer window to connect to source control
//   3. Use the Output window to see build output and other messages
//   4. Use the Error List window to view errors
//   5. Go to Project > Add New Item to create new code files, or Project > Add Existing Item to add existing code files to the project
//   6. In the future, to open this project again, go to File > Open > Project and select the .sln file

# sum-calculator
adds as many numbers the user inputs

#include <iostream>
using namespace std;

void sumCalculator()
{
    int numCount;
    double input;
    double total = 0;
    cout << "Enter how many numbers you want to add: ";
    cin >> numCount;
    for (int i = 0; i < numCount; i++)
    {
        cout << "Enter number " << i+1 << ": ";
        cin >> input;
        total+=input;
    }
    cout << "Your sum is " << total << endl;
}

int main()
{
    cout << "This program will allow you to calculate the sum of how many numbers you would like" << endl;
    sumCalculator();
    return 0;
}

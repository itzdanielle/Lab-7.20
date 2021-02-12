# Lab-7.20
#include <iostream>
using namespace std;

int main() {
  int number;
  
  cout << "Enter a number between 1 and 10: ";
  cin >> number;
  
  if ((number > 2) && (number < 6)) 
    cout << "Your number is between 2 and 6.\n";

  if ((number < 3) || (number > 7)) 
    cout << "Your number is less than 3 or greater than 7.\n";
    
    
  
    
}

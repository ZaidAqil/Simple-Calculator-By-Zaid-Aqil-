# Simple-Calculator-By-Zaid-Aqil-
Za8's Simple Calculator :)
This Project is mostly about creating a simple programme to do simple maths.:)

// Za8 Aqil's Simple yet Cool Calculator :) 
//Dr Nor Hafeizah
// The Simple Calculator Assesment.
#include <iostream>
#include <string>
using namespace std;

int main()
{
    char op;
    float num1,num2; 
    //Operator Selection
    cout << "Enter Operator Either +,-,* or / :" ;
    
    cin >> op;
    
    
    cout << "Enter 2 Numbers";
    cin >> num1;
    cin >> num2;
     
     switch(op)
     {
         case '+':
         cout << num1+ num2;
         break;
         //Addition
         
         case '-':
         cout << num1-num2;
         break;
         //Subtraction 
         
         case '*':
         cout << num1*num2;
         break;
         //Multiplication
         
         case '/':
         cout << num1/num2;
         break;
         //Division
         
         default :
         //Other than the op an error message will pop-up
         cout<< "Error! Unknown Operator Keyed-In.:(.Please Try Another Operator Following The Symbols Given :))";
         break;
         
     } 
     
     k thanks bye :)

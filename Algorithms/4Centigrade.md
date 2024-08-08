# Temperature of a city in Fahrenheit degrees is input through the keyboard. Write a program to convert this temperature into Centigrade degrees.
Hint: Centigrade = (Fahrenheit – 32) *5/9

### Algorithm
1. Input two variables Centigrade and Fahrenheit.
2. Caculate Centigrade = (Fahrenheit -32) * 5/9
3. Print Centigrade

### Flow-chart
```mermaid
graph TD;
    Start-->InputCentigradeandFahrenheit;
    InputCentigradeandFahrenheit-->CaculateCentigrade(Fahrenheit-32)*5/9;
    CaculateCentigrade(Fahrenheit-32)*5/9-->PrintCentigrade;
    PrintCentigrade-->End;
```
### C++ code
```c++
#include <iostream>
using namespace std;
int main() {
float Centigrade,Fahrenheit;
  cout<<"Input Fahrenheit ";
cin>>Fahrenheit;
  Centigrade = (Fahrenheit-32)*5/9;


cout<<"**********************";
cout<<endl;
cout<<" Centigrade is : "<<Centigrade;


  return 0;
}
```

![image](https://github.com/user-attachments/assets/82bacd44-998b-4cfb-9773-d212561091e0)# OOP
First OOP Program
#include <iostream> <br>
using namespace std;<br>
class bike { <br>
public:<br>
string name;<br>
int MaxVelocity;<br>
string color;<br>
void Detail() {<br>
 cout<<"Bike is:"<<name<<endl;<br>
   cout<<"Bike is:"<<color<<endl;<br>
 cout<<"Bike is:"<<MaxVelocity<<endl;<br>
}<br>
};<br>
int main() {<br>
bike bike1;<br>
  bike1.name = "YAMAHA";<br>
   bike1.MaxVelocity = 249.99;<br>
     bike1.color = "red";<br>
      bike1.Detail();<br>
      cout<<endl;<br>
     bike bike2;<br>
    bike2.name = "SUZUKI";<br>
   bike2.MaxVelocity = 310.99;<br>
 bike2.color = "black";<br>
bike2.Detail();<br>
}<br>


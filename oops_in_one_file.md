
  Class: 
  1. A class is a user-defined datatype and serves as a blueprint or template for creating objects.
  2. It defines the structure(attributes) and behaviour(methods) that the object created from it will have.
  3. A class itself does not occupy memory until an object in instantiated.

  Object:
  1. An object is a real-world entity and is an instance of a class.
  2. It has attributes(data members) and behaviors(methods / member function) defined by the class.
  3. Unlike class, an object occupies space in memory.

    
  Access Modifiers:
  1. Private: Data and Members accessible inside the class.
  2. Public: Data and members accessible to everyone.
  3. Protected: Data and members accessible inside the class and to its derived class.
   
#include<string>
using namespace std;
class Teacher{
  public:
   string name,dept,subj,salary;
  void changedept(string newDept){
    dept=newDept;
  }
}; 
  We use setter() and getter() function to set and get the private values. 
  

  /* Definition of OOPs*/
  OOPs: Object Oriented Programming is a modular approach where emphasis is one data rather than function to increase the productive logic.
  
  4 Pillars of OOPs:
    1. Encapsulation
    2. Inheritance
    3. Polymorphism
    4. Abstraction


   1.Encapsulation 
![ecapsulation_in_cpp](https://github.com/user-attachments/assets/9ced5cdd-0f18-415f-ad62-0f0fd9c36b10)
Encapsulation is the wrapping up of data and member functions in a single unit called class.
It is used for data hiding also where we use private access modifier for hiding the data and members.
 class Account{
 private:
 double balance;
 string password;
 public:
 string accountId;
 string username;
 };
 

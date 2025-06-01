# 💡 Object-Oriented Programming (OOP) in C++

---

## 📘 Class

1. A **class** is a user-defined data type and serves as a blueprint or template for creating objects.
2. It defines the **structure (attributes)** and **behavior (methods)** that the objects created from it will have.
3. A class **does not occupy memory** until an object is instantiated.

---

## 🧱 Object

1. An **object** is a real-world entity and is an instance of a class.
2. It has **attributes (data members)** and **behaviors (methods / member functions)** defined by the class.
3. Unlike a class, an object **occupies space in memory**.

---

## 🔐 Access Modifiers

| Modifier   | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| `private`  | Data and members accessible **only inside the class**                       |
| `public`   | Data and members accessible **to everyone**                                 |
| `protected`| Data and members accessible **inside the class and its derived classes**    |

---

## 💻 Example: Class & Object in C++

```cpp
#include <string>
using namespace std;

class Teacher {
public:
    string name, dept, subj, salary;

    void changeDept(string newDept) {
        dept = newDept;
    }
};
```
☝️ We use setter() and getter() functions to set and get private values.
## 📌 What is OOP?
Object-Oriented Programming (OOP) is a modular approach where the emphasis is on data rather than functions, aiming to write productive and reusable logic.
.

🌟 4 Pillars of OOP

1. Encapsulation
2. Inheritance
3. Polymorphism
4. Abstraction

🔒 1. Encapsulation
Encapsulation is the wrapping up of data and member functions into a single unit called a class.

It is used for data hiding, where we use the private access modifier to hide internal data and members.

It improves modularity, security, and maintainability of the code.

🖼️ Diagram:![ecapsulation_in_cpp](https://github.com/user-attachments/assets/60924a76-6234-4f62-a277-282a15ca38e3)
```cpp
class Account {
private:
    double balance;
    string password;

public:
    string accountId;
    string username;

    void setBalance(double b) { balance = b; }
    double getBalance() { return balance; }
};
```

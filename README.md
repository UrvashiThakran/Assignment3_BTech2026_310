# Assignment3_BTech2026_310

# Coding Questions : 29.01.25

OOPS:

Problem Statement:

Ques1:Virtual Function Implementation

Platform Used:
Programiz

Approach:Polymorphism

Code1:

#include<iostream>
using namespace std;
class Base
{
    public:
    void Vrindavan()
    {
        cout<<"******VRINDAVAN IS MY DREAM PLACE*******"<<endl;
    }
    virtual void Barsana()
    {
        cout<<"Base Class:It is very precious to me ,more then my life"<<endl;
    }
};
class Derived:public Base
{
    public:
    void Vrindavan()
    {
        cout<<"Vrindavan is the Home of RadheKrishna"<<endl;
    }
    void Barsana()
    {
        cout<<"Radha Rani is the king of vrindavan and Barsana";
    }
};
    int main()
    {
         Derived D;
         Base B;
         Base *base_ptr;
         base_ptr=&B;
         base_ptr->Vrindavan() ;
         base_ptr->Barsana() ;
         base_ptr=&D;
         base_ptr->Vrindavan() ;
         base_ptr->Barsana();

        return 0;
    }


DBMS:

Platform Used:LeetCode

 Ques 1:Delete Duplicate Emails

 Code 1:

SELECT MAX(salary) AS SecondHighestSalary
FROM Employee
WHERE salary < (SELECT MAX(salary) FROM Employee);

 DSA:

 

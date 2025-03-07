# GYM-Management-System-
Designed a text-based menu system for managing memberships Developed a billing system that calculates membership fees dynamically.
#include <iostream> 
using namespace std; 
int main() 
{ 
while (true) 
{ 
int choice, month, bill; 
cout << "\t\t\t\t''''''''''''''''''''''''''''''''''''''" << endl; 
cout << "\t\t\t\t\t GYM Management System" << endl; 
cout << "\t\t\t\t1. For the Students" << endl; 
cout << "\t\t\t\t2. For the Business Man" << endl; 
cout << "\t\t\t\t3. For the Employee " << endl; 
cout << "\t\t\t\t4. To Exit the Program" << endl; 
cout << "\t\t\t\t''''''''''''''''''''''''''''''''''''''" << endl; 
cin >> choice; 
if (choice == 1 || choice == 2 || choice == 3) 
{ 
switch (choice) 
{ 
case 1: 
cout << "''''''''''''''''''''''''''''''''''''''" << endl; 
cout << "Enter No of Month : "; 
cin >> month; 
bill = month * 300; // 300 for Student 
cout << "Your Bill is:" << bill << endl; 
cout << "Thanks For Joining !!" << endl; 
cout << "''''''''''''''''''''''''''''''''''''''" << endl; 
                break; 
            case 2: 
                cout << "''''''''''''''''''''''''''''''''''''''" << endl; 
                cout << "Enter No of Month : "; 
                cin >> month; 
                bill = month * 500; // 500 for the employees 
                cout << "Your Bill is:" << bill << endl; 
                cout << "Thanks For Joining !!" << endl; 
                cout << "''''''''''''''''''''''''''''''''''''''" << endl; 
                break; 
            case 3: 
                cout << "''''''''''''''''''''''''''''''''''''''" << endl; 
                cout << "Enter No of Month : "; 
                cin >> month; 
                bill = month * 700; // 700 for business man 
                cout << "Your Bill is:" << bill << endl; 
                cout << "Thanks For Joining !!" << endl; 
                cout << "''''''''''''''''''''''''''''''''''''''" << endl; 
                break; 
            } 
        } 
        if (choice == 4) 
        { 
            exit(0); 
        } 
        if (choice > 4) 
        { 
            cout << "You enterd a Wrong Value So Please Run the Program Again !" << endl; 
        } 
    }
}

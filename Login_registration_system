#include <iostream>
#include <string>
using namespace std;

int main() {
    string username, password;
    int choice;

    cout << "1. Register\n2. Login\nEnter choice: ";
    cin >> choice;

    if (choice == 1) {
        cout << "Enter Username: ";
        cin >> username;
        cout << "Enter Password: ";
        cin >> password;
        cout << "\nRegistration Successful!\n";
    } 
    else if (choice == 2) {
        string u, p;
        cout << "Enter Username: ";
        cin >> u;
        cout << "Enter Password: ";
        cin >> p;

        if (u == username && p == password)
            cout << "\nLogin Successful!\n";
        else
            cout << "\nInvalid Login!\n";
    }
    return 0;
}

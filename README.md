#include <iostream>
using namespace std;

int main() {
    string username, password;

    cout << "Enter username: ";
    cin >> username;

    cout << "Enter password: ";
    cin >> password;

    if (username == "Nikhil" && password == "1234") {
        cout << "Login Successful!";
    } else {
        cout << "Invalid Username or Password!";
    }

    return 0;
}

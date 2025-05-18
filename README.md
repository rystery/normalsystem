#include <iostream>
#include <string>
using namespace std;

int main() {
    int balance = 1400;
    string dogao = "fudido";

    cout << "********************************************************************************************************************************\n";
  

    cout << "Hi my friend, what do you want today?\n";
    cout << "1. balance\n";
    cout << "2. nomedodogao\n";

    cout << "********************************************************************************************************************************\n";

    int choice{};
    cout<< "choose the number:" , cin >> choice;

    if (choice == 1) {
        cout << "Your balance is:" << balance << endl;
    }
    else if (choice == 2) {
        cout << "Nome do seu cachorro e: " << dogao << endl;
    }
    else {
        cout << "Valor errado" << endl;
    }

    return 0;
}

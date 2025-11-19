include <iostream>
using namespace std;

int main() {
    double a, b;

    cout << "Enter first number: ";
    cin >> a;

    cout << "Enter second number: ";
    cin >> b;

    if (b == 0) {
        cout << "Error: Cannot divide by zero!" << endl;
    } else {
        double result = a / b;
        cout << "Result: " << result << endl;
    }

    return 0;
}


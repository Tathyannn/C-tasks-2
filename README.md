#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double x, a, y;
    cout << "x="; cin >> x;
    cout << "a="; cin >> a;

    if (x > 5) {
        y = cos(abs(x));
    } 
    else if (x < -5) {
        y = a;
    } 
    else {
        y = (1 + a * pow(a, 2)) * pow(a, x); 
    }

    cout << "y=" << y << endl;
    return 0;
}



int main() {
    double x, y, z;

    cout << "x="; cin >> x;
    cout << "y="; cin >> y; 

    if (x / 2.5 + y / 1.5 <= 1 && y >= -x + 1) {
        z = sin(x);
    } 
    else {
        z = cos(x);
    }

    cout << "z=" << z << endl;
    return 0;

}





int main() {
    int n, x, y;
    float s;

    cout << "n="; cin >> n;
    s = n;
    x = 1;
    y = 1;

    while (x <= n / 2) {
        if (n % x == 0) {
            s = s + x;
            y++;
        }
        x++;
    }

    cout << "s=" << s / y << endl;
    return 0;

}





int main() {
    int x, n;
    cout << "n="; cin >> n;

    x = 1;
    while (x <= n) {
        x = x * 2; 
    }

    cout << "x=" << x << endl;
    return 0;

}

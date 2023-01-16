#include <iostream>
using namespace std;
int main() {
    int x, y, z;
    cin>>x;
    cin>>y;
    cin>>z;
    if (x + y > z) {
        cout<<x + y - z;
    } else {
        cout<< "Impossible";
    }
    return 0;
    }

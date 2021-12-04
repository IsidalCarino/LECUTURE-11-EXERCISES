# For Loop, Table
```
#include <iostream>
using namespace std;
int main()
{
    int y;
    cout << "Enter a number you want the table of: " << endl;
    cin >> y;
    while (cin.fail())
    {
        cout << "Invalid command enter the number again." << endl;
        cin.clear();
        cin.ignore(1000, '\n');
        cin >> y;
    }for (int x = 0; x <= 10; x++) {
        cout << y << "x" << x << "=" << y * x << endl;
    }
}
```
# While Loop, Table (Convert the previous code into while loop)
```
```
# For Loop, Table (Table counts till 12)
```
#include <iostream>
using namespace std;
int main()
{
    int y;
    cout << "Enter a number you want the table of: " << endl;
    cin >> y;
    while (cin.fail())
    {
        cout << "Invalid command enter the number again." << endl;
        cin.clear();
        cin.ignore(1000, '\n');
        cin >> y;
    }for (int x = 0; x <= 12; x++) {
        cout << y << "x" << x << "=" << y * x << endl;
    }
}
``` 
# Do-While Loops, Find the 9s
```
```

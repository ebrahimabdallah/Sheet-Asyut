```
#include<iostream>
#include <numeric>
#include<string>

using namespace std;

int main()
{
    long long count;
    cin >> count;
    int arr[count];

    for (int i = 0; i < count; i++) {
        cin >> arr[i];
    }
    for (int i = 0; i < count; i++)
    {
        if (arr[i] < 0)
        {
            arr[i] = 2;
        }
        else if (arr[i] > 0)
        {
            arr[i] = 1;
        }
    }
        for (int i = 0; i < count; i++)
        {
            cout << arr[i]<<" ";
        }
    }
```

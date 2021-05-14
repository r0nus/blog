---
title: "Hello world"
date: 2021-05-15T00:50:40+05:30
Description: ""
Tags: []
Categories: []
DisableComments: false
---

```cpp

#include <iostream>
using namespace std;
int main(int argc, char const *argv[])
{

    char arr[17] = "abcdefghijklmnop";
    int t;
    cin >> t;
    for (int i = 0; i < t; i++)
    {
        int n, p = 0;
        cin >> n;
        char s[n + 1];
        cin >> s;
        for (int j = 0; j < n / 4; j++)
        {
            int k = 0, s = 0, e = 15, z;
            while (k < 4)
            {
                int mid = s + e / 2;
                if (s[p] == '0')
                {
                    e = mid + 1;
                }
                else
                {
                    s = mid + 1;
                }
                z = mid;
                k++;
                p++;
            }
            cout << arr[z];
        }
        cout << endl;
    }

    return 0;
}

```

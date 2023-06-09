# Smileface

Here is an example of switching C++ datatypes (implicit conversions).

```
#include <iostream>
using namespace std;


void func(int a, char b) {
    cout << b << endl;
}

int main() {
    func(1, 2.32);
}
```


I change **a** datatype from _double_ to _char_ (actally _double -> int -> char_)

The output of the program shows average every c++ programmer face. Try it now.

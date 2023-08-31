* `iostream` library
* It has a two sub parts
  * `istream`
    * `cin`
  * `ostream`
    * `cout`, `cerr`, `clog`


```
#include <iostream>  // header
int main()
{
  std::cout << "Enter two numbers:" << std::endl; // similar to (std::cout << "Enter two numbers:") << std::endl;
  int v1 = 0, v2 = 0;
  std::cin >> v1 >> v2;
  std::cout << "The sum of " << v1 << " and " << v2 << " is " << v1 + v2 << std::endl;
  return 0;
}
```

* The `<<` operator takes two operands: The left-hand operand must be an `ostream` object. the right-hand operand is a value to print. The operator writes the given value on the given ostream.
* Writing endl has the effect of ending the current line and flushing the buffer associated with that device. Flushing the buffer ensures that all the output the program has generated so far is actually written to the output stream, rather than
sitting in memory waiting to be written.
* The prefix `std::` indicates that the names `cout` and `endl` are defined inside the namespace named `std`.  NameSpace prevents name collision. All the names defined by the standard library are in the std namespace.
* `::` is scope operator.

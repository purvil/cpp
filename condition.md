## if else
```
if (val == currVal) // if the values are the same
 ++cnt; // add 1 to cnt
else { // otherwise, print the count for the previous value
 std::cout << currVal << " occurs " << cnt << " times" << std::endl;
 currVal = val; // remember the new value
 cnt = 1; // reset the counter
}
```

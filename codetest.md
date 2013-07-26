```cpp
// program.cpp
#include <stdio.h>

template<class T> T samplefunc(T val);

int main() {
  printf("%d\n", samplefunc(10));
	return 0;
}

// samplefunc_impl.hpp
template<class T>
T samplefunc(T val) {
	return val*val;
}

template int samplefunc<int>(int);
```

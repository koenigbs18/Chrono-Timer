# Chrono-Timer
Simple template-based class timer utilizing the chrono library.
Chrono Library: https://en.cppreference.com/w/cpp/chrono

Compiled with latest C++20 features (std:c++latest)

# Basic Example
```C++
	//Timer<(Chrono clock type)> t;
	Timer<std::chrono::steady_clock> t;
	t.start();
	if(t.get_elapsed_ms().count() < i) {
		//...
	}
```

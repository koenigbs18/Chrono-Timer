# Chrono-Timer
Simple template-based class timer utilizing C++11's chrono library.

#Usage
```C++
      //Timer<(Chrono clock type)> t;
		  Timer<std::chrono::steady_clock> t;
		  t.start();
		  if(t.get_elapsed_ms().count() < i) {
		    //...
      }
```

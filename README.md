# Using micros() and delay_us() with STM32 
## 1. include micros.h
```
#include "micros.h"
```

## 2. initialization of DWT
```
DWT_Init()
```

# 3. use funtion
```
uint32_t us_time = micros();
~~~
delay_us(500);
```

## DHT11 STM32 Library
 DHT11 STM32 Library using HAL Drivers
---
## Usage
-You need to set timer freq to 1 us. 

```c
// code away!
dht11_t dht;
init_dht11(&dht, &htim2, dht11_1_GPIO_Port, dht11_1_Pin);
readDHT11(&dht);
```
-Tested on STM32L071RZ

## Preferences
1. http://www.elektrobot.net/stm32-dht11-ve-uart-kullanmi/
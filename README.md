
DHT11 HAL Library with Timer for STM32 MCU's.

When create new project with CubeMX select to TIM1,TIM2,TIM3.

Example:

Structure; DHT11_Dev dht11
Init     ; DHT11_Init(&dht11,TIM3,GPIOA,GPIO_PIN_8)
Read     ; int temp = DHT11_Read(&dht11)

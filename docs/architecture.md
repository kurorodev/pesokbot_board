# Архитектура Робота "Пуля" V2

## Колесная база:
 - Multibot 4-ех колесная Mecanum база.
 - Моторы DC 12V with Encoder 
 - H-type Motor Drivers

## Питание
 - 3S2P связка от Multibot 18650 аккумуляторы
 - TVS однополярный 
 - BMS
 - Magnetic Mounting for DC-DC Comprehensive Power Supply System Implemented voltage rails: 3.3V, 5V, 12V and adjustable voltage. 
 - Питание RPi5 должно 5А 5В(отдельный блок аккумуляторов под это)

## Серво
 - 4x Feetech STS3215
 - порожняковый на раскрытие клешни 

## Манипулятор
 - Кастомный манипулятор на крышке колесной базы по центру.
 - Степень свободы: 4
 - Серво: 5(основание, выше верх-низ, еще выше вглубь наклон, основание клешни, клешня)
 - Наличие камеры на манипуляторе(камера с минимальным зумом(Camera Module 3 RPi)

## Камера глубины
 - Intel RealSense с Центра. Установка непосредственно на переднюю часть телеги

## Датчик линии
 - Датчик линии для езды по линии(в том числе и прерывистой) Pololu QTRX-HD-15A

## Микроконтроллер
 - STM32H743ZIT6

## Высокоуровневый мозг
 - RaspberryPi5 + AI HAT Hailo 26 TOPS

## Датчики расстояния
 - 5x vl53l1x distance sensor (RR, RF, LR, LF, FF)

## IMU
 - BNO086

## USB
 - USB-C for flash firmware MCU
 

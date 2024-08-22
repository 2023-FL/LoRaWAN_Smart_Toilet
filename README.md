# LoRaWAN_Smart_Toilet
Smart Toilet with LoRaWAN Gateway and LoRa node sensors
The following disgram is LoRa Gateway, in which it contains Backend pladtform of Node-Red, LoRaWAN Gateway Application, LoRaWAN Network and hardware Layers
![image](https://github.com/user-attachments/assets/208473d2-8903-4958-8449-2269ea852e66)

I applied LoRa ESP32 MCU as LoRa node sensors, in which there firmware codes of two LoRa ESP32 MCU can commnicate with each others and send package to LoRaWAN Gateway regularly;
LoRa ESP32 sensor 2 conected with IR sensor for detecting any person approaching to toilet, if there is person reaching to toilet, LoRa ESP32 sensor 2 will send anaulog signal to LoRa ESP32 sensor 1 via LoRa protocol; meanwhile, LoRa ESP32 sesnor 2 will send packet to LoRaWAN Gateway. When LoRa ESP32 sensor 2 received sensor 1's signal, the UVC lamp will be turned off if the UVC strilization process was lunached on schedule in accordance with firmware programming.
LoRa ESP32 sensor 1, which connect with UVC lamp for sterilization
![image](https://github.com/user-attachments/assets/0e8ba688-04fd-4961-a94e-5182dbf8880c)

Below is LoRaESP32 sensor 2, which connects with IR sensor
![image](https://github.com/user-attachments/assets/df26da2b-f24c-4fb4-8508-d6f98d9aeb26)

[YouTube URL] (https://youtu.be/uDdYT3XUZX0)

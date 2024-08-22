# LoRaWAN_Smart_Toilet
Smart Toilet with LoRaWAN Gateway and LoRa node sensors:
The advantages of LoRa-based ESP32 sensor can provide low power consumption and a better propagation for long distance with LoRaWAN network than WiFi network if there is metallic materials applied in the indoor renovation of shopping mall, these metallic materials can absorpt electromagnetic wave transmitted from WiFi router over the toilet area of each floor of shopping mall. On contratry, there is a stronger propagation of LoRaWAN network that won't be affected of LoRaWAN siganl by those metallic materials of the indoor renovation setting.
The following diagram is LoRa Gateway, in which it contains Backend pladtform of Node-Red, LoRaWAN Gateway Application, LoRaWAN Network and hardware Layers
![image](https://github.com/user-attachments/assets/208473d2-8903-4958-8449-2269ea852e66)

I applied LoRa ESP32 MCU as LoRa node sensors, in which there firmware codes of two LoRa ESP32 MCU can commnicate with each others and send package to LoRaWAN Gateway regularly;
LoRa ESP32 sensor 2 conected with IR sensor for detecting any person approaching to toilet, if there is person reaching to toilet, LoRa ESP32 sensor 2 will send anaulog signal to LoRa ESP32 sensor 1 via LoRa protocol; meanwhile, LoRa ESP32 sesnor 2 will send packet to LoRaWAN Gateway. When LoRa ESP32 sensor 2 received sensor 1's signal, the UVC lamp will be turned off if the UVC strilization process was lunached on schedule in accordance with firmware programming.

Below two LoRa ESP32 sensors are prototype. LoRa ESP32 sensor 1 connects with UVC lamp for sterilization.
![image](https://github.com/user-attachments/assets/0e8ba688-04fd-4961-a94e-5182dbf8880c)

LoRaESP32 sensor 2 connects with IR sensor set on the ceiling of each bloack of toilet for detecting any user approaching to the certain toilet. If anyone is approaching to the toilet and there UVC lamp was running, the LoRa sensor 2 will send anauloge signal to LoRa sensor 1 to stop the UVC lamp immediately.
![image](https://github.com/user-attachments/assets/0614894e-40e9-48db-b666-e381bd5ac1d9)

Furthermore, I have applied LiDAR Radar sensor for detecting anyone falling down on the toilet floor but do not disclose personal image anginst privacy ordiance (privacy law) and make the end-user embarring. (The video is under oncstruction!)

[YouTube URL] (https://youtu.be/uDdYT3XUZX0)

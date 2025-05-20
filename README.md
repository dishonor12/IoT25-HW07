# IoT25-HW07

# LED


https://github.com/user-attachments/assets/cd8c28d6-152f-45f2-a96b-11dc7a21df92


# Web Server
![KakaoTalk_20250520_210903491](https://github.com/user-attachments/assets/30f8bfe8-4f5a-4012-83cb-e8b9a72a5974)

# Serial Monitor

![스크린샷 2025-05-20 212226](https://github.com/user-attachments/assets/1ddb391b-b6ab-4749-9bc2-8aad12232b84)

# Chart

<img width="482" alt="KakaoTalk_20250520_210944645" src="https://github.com/user-attachments/assets/0d94d87e-9689-4b8c-9480-9c4cd30f23cc" />


# Explaination
## Client Summary:
Wifi.begin() for WiFi connection

WiFiClient to handle the TCP connection

client.print() or client.write() to send message

Delay or timer for periodic data sending

## Server Summary:
WiFiServer.begin() to start listening
server.available() to accept clients
client.read() or client.readStringUntil() to receive data
Feedback sent using client.print() or client.write()

## Test Case
Client connects to WiFi -> SSID and password correctly set (Success)
Client connects to server IP:Port -> Ensure same subnet and open port (Depends on network)
Client sends data -> Verified by Serial Monitor (Success)
Server receives data -> Output shows data received correctly (Success)
Server sends response -> Clients logs confirm receipt of data (Success)
Connection handling -> Graceful handling of dropped connections (Needs improvement)

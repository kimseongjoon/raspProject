# MQTT프로토콜을 이용한 LED 제어

## 1. 개요
서버에 Mosquitto Broker Server를 실행하고, 라즈베리파이에서 Flask를 통한 웹페이지 제공, MQTT sub, pub기능, LED 제어 기능을 구현하여 MQTT프로토콜 사용 프로젝트를 진행함

## 2. 실행방법
1. Broker서버를 설치할 컴퓨터에서 [https://mosquitto.org/download/](https://mosquitto.org/download/)접속후 Mosquitto 다운로드 및 설치 후 서비스 실행
2. Fritzing 회로도와 같이 라즈베리파이 10번핀에 LED를 연결
3. 라즈베리파이에서 Python flask, paho-mqtt 라이브러리 설치
3. 해당 깃 내용을 복사하고 mattp.py, matts.py 실행
4. http://'라즈베리 파이 ip주소':5000/ 로 접속하여 웹페이지에서 LED 제어

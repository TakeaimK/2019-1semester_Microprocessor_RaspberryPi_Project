# 2019-1semester_Microprocessor_RaspberryPi_Project

### 2019-1학기 마이크로프로세서및실험 라즈베리파이 활용 프로젝트 - Kiosk 제작

![KakaoTalk_20190530_103742420](https://user-images.githubusercontent.com/44010902/68175886-10aea800-ffc6-11e9-87c0-46a80fed61b9.png)
![KakaoTalk_20190530_103742420_06](https://user-images.githubusercontent.com/44010902/68175887-10aea800-ffc6-11e9-9fe9-a7b2c48e3c8c.png)
![KakaoTalk_20190530_103742420_08](https://user-images.githubusercontent.com/44010902/68175888-10aea800-ffc6-11e9-9a4b-4309939806d9.png)

---

IDE : Eclips Oxygen  
Language : Java(Client), Python(Server)
Adviser : Kim Young-cheon  

### Team Member

Server : Park Kyung-hyun, Seo Eun-bin  
Client : Choi Se-jin(Leader), Gong Ji-na

### How to use

1. Install JVM on Raspberry Pi
2. Run Server and Client

---

라즈베리파이 활용 프로젝트입니다.  
저희 팀은 Kiosk (무인 주문기)를 제작하였으며, 회전초밥 가게를 컨셉으로 잡고 제작하였습니다.  
먼저 Server는 소켓 통신을 활용하여 일반 PC에서 실행 가능한 Python Program으로 제작되었습니다. 이곳에서는 Client에서 주문하기를 누르면, Server의 Console에 Client로부터 전송된 문자열 데이터를 분리하여 주문 주문한 테이블과 품목, 수량이 출력됩니다.  
Client는 ARM Processor에서도 구동 가능하도록 Java Swing으로 제작된 GUI Client이며, 실행 시 메뉴 주문 화면이 나오고, 주문 완료 시 Server로 문자열 형태의 데이터가 전송됩니다.  
장점으로는 구축 비용이 다른 Kiosk보다 저렴합니다. Server부터 Client까지 하드웨어 비용이 매우 저렴합니다.

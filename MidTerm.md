# 중간고사

- 이름 : 최수진
- 학번 : 2023310028

- 답안 :

1. AWS Clean up Screen shots

답)
<img width="1917" height="867" alt="image" src="https://github.com/user-attachments/assets/20ba74d8-8ec9-4972-81e6-8ce5e09210cd" />
<img width="1917" height="867" alt="image" src="https://github.com/user-attachments/assets/be1757f9-a706-4d03-b9ae-94b93f188f04" />


2. EC2 instance Domain name

답) iotlab2.freedynamicdns.net

3. Explain MQTT and why it is regarded good for IoT?

답) 
 MQTT는 IoT를 위한 OASIS 표준 메시징 프로토콜이다. 매우 가벼운 발행/구독 메시징 전송방식으로 설계되어, 코드 용량이 작고, 네트워크 대역폭 사용량이 최소화된 상태에서 원격 장치를 연결하는데 이상적이다. IoT 디바이스는 일반적으로 리소스 제약이 있는 네트워크를 통해 제한된 대역폭으로 데이터를 전송하고 수신해야 한다. MQTT는 이러한 IoT 디바이스의 데이터 전송에 사용할 때, 구현이 쉽고 데이터를 효율적으로 전달할 수 있다. 즉, 수많은 센서들이 동시에 작동하고, 실시간으로 데이터를 주고받는 구조를 떠받들어주는 기술이다.

 MQTT 프로토콜은 게시/구독 모델의 원칙을 기반으로 작동한다. 전통적인 네트워크 통신에서는 클라이언트와 서버가 서로 직접 통신한다. 클라이언트가 서버의 리소스 또는 데이터를 요청하면 서버가 이를 처리한 후 응답을 다시 보낸다. 그러나 MQTT는 게시/구독 패턴을 사용하여 메시지 게시자(Publisher)와 메시지 구독자(Subscriber)를 분리한다. 대신에 메시지 브로커라고 하는 제3의 구성 요소가 게시자와 구독자 간의 통신을 처리한다. 이 브로커가 하는 일은 게시자로부터 수신되는 모든 메시지를 필터링하고 구독자에게 직접 배포하는 것이다. 게시자와 구독자는 서로의 네트워크 위치를 모르며, IP주소 또는 포트 번호와 같은 정보를 교환하지 않는다. 또한 동시에 실행되거나 네트워크를 통해 연결되지 않고, 서로를 중단시키지 않은 채 메시지를 전송하거나 수신할 수 있다. 구독자는 게시자가 메시지를 전송할 떄까지 기다리지 않아도 된다.
 MQTT는 가볍고 효율적이며, 양방향 통신(단방향 제어보다 훨씬 유연하고 효율적인 구조)가 가능하다. 또한 수백만개의 사물로 확장이 가능하고, 신뢰할 수 있는 메시지 전달이 가능하다. 작고 빠르며, 연결을 최소한으로 유지하면서도 실시간으로 반응이 가능하기 때문에, HTTP 방식보다 훨씬 유리하다. 이처럼 MQTT는 하나의 브로커를 통해 수십개 장비와 데이터가 오가는 복잡한 구조를 효울적으로 관리하며, 전체 시스템의 확장성과 반응성을 높인다. 이러한 점이 IoT 시스템에 적합한 이유이다.



4. 3 Device IoT Thermostat

답) https://github.com/iot201-2026-ChoiSujin/Midterm2026_NodeRed

5. 3 Device IoT Thermostat Video

답) 

https://github.com/user-attachments/assets/042e678e-0eff-4a96-a2db-226f7f6b4ee3



6. AWS Re Start Lab Check

답)

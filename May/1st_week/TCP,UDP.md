
# TCP

- 연결 지향 방식이다.
- 3-way handshaking과정을 통해 연결을 설정하고 4-way handshaking을 통해 해제한다.
- 흐름 제어 및 혼잡 제어.
- 높은 신뢰성을 보장한다.
- UDP보다 속도가 느리다.
- 전이중(Full-Duplex), 점대점(Point to Point) 방식.

---


- TCP 통신이란?

- reliable network를 보장한다는 것은 4가지 문제점 존재

- 흐름제어/혼잡제어란?

- 전송의 전체 과정



#### 1. 흐름제어 (Flow Control)

<br>

#### 2. 혼잡제어 (Congestion Control)





---

<br>

# UDP

- 비연결형 서비스로 데이터그램 방식을 제공한다
- 정보를 주고 받을 때 정보를 보내거나 받는다는 신호절차를 거치지 않는다.
- UDP헤더의 CheckSum 필드를 통해 최소한의 오류만 검출한다.
- 신뢰성이 낮다
- TCP보다 속도가 빠르다
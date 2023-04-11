# 모니터
mutual exclusion을 보장
조건에 따라 스레드가 대기 상태로 전환 가능

### 언제
- 한번에 하나의 스레드만 실행돼야 할 대
- 여러 스레드와 협업이 필요할 때

### 구성 요소
- mutex
- condition variable

### 큐 2개
- entry queue
> critical section에 진입을 기다리는 큐

- waiting queue
> 조건이 충족되길 기다리는 큐

wait는 while안에

# 자바 예시

자바에서 모니터란
모든 객체가 모니터 갖고있음


# Queue
## 1. 큐(Queue)
- 사전적 의미로는 줄을 서서 기다리는 것을 의미
## 2. 큐 자료구조(Queue data structure)
- 한쪽 끝에서는 삽입 작업이 이루어지고 반대쪽에서는 삭제 작업이 이루어지는 자료구조
  - 예를 들어서 고객이 은행에서 순서대로 번호표를 뽑고, 번호표 순서대로 먼저 온 고객부터 업무 처리를 해 주는 것을 들 수 있다.
## 3. 리어(Rear)
- 원소 삽입 연산만 이루어지는 곳을 의미
  - 예를 들어서 마지막에 은행에 오신 고객의 번호표를 들 수 있다.
## 4. 프론트(Front)
- 원소 삭제 연산만 수행되는 곳을 의미
  - 예를 들어서 먼저 은행에 오신 고객의 번호표를 들 수 있다.
## 5. 피크(Peek)
- Front에 위치한 원소를 읽는 것을 의미
  - 예를 들어서 먼저 은행에 오신 고객이 누구인지를 확인하는 것을 들 수 있다.
## 6. 인큐(Enqueue)
- 맨 뒤에 어떠한 원소를 삽입하는 것을 의미
  - 예를 들어서 마지막으로 은행에 오신 고객에게 번호표 발부하는 것을 들 수 있다.
## 7. 디큐(Dequeue)
- 맨 앞쪽의 원소를 삭제하는 것을 의미
  - 예를 들어서 은행창구에서 업무처리를 완료한 고객의 번호표를 대기목록에서 삭제하는 것을 들 수 있다.
## 8. 큐의 특징(Queue character)
- 각각의 연산작업만 수행된다.
- 가장 첫 원소와 끝 원소로만 접근이 가능하다.
- 프론트 원소는 가장 먼저 큐에 들어왔던 원소가 된다.
- 리어 원소는 가장 늦게 큐에 들어온 마지막 원소가 된다.
- FIFO(First in First out)방식
  - 선입선출방식
  - 먼저 들어간 프론트 원소가 먼저 삭제된다.
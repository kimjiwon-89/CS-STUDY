# 스택(Stack) & 큐(Queue) 질문

## 경미
### 스택과 큐 실사용 예시는?
스택은 자바의 스택 메모리 영역에 사용됩니다. 지역변수와 매개변수 데이터 값이 저장되는 공간이고, 메소드 호출 시 메모리에 푸쉬하고 종료되면 pop해서 삭제합니다. 
큐는 자원의 할당과 회수를 하는 스캐쥴러 역할을 하는 OS의 스케쥴러에서 쓰입니다.

### 스택과 큐의 차이점?
스택은 후입선출(LIFO, Last In First out) 구조로 나중에 들어온 데이터가 먼저 나가는 구조입니다. 보통 브라우저의 뒤로가기 버튼이나 실행 취소 기능에 활용합니다.

큐는 선입선출(FIFO, First In First Out) 구조로 먼저 들어온 데이터가 먼저 나가는 구조입니다. 프린터 작업 관리, 프로세스 스케줄링 등에 활용됩니다. 

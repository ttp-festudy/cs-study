# TCP 핸드셰이킹

작성자: 김진우

TCP에서 연결형 서비스를 지원하기 위해 송신부와 수신부를 연결하는 과정을 거친다. 연결을 시작할 때는 <strong>3-way 핸드셰이킹</strong>, 연결을 종료할 때는 <strong>4-way 핸드셰이킹</strong>을 한다.

### 핸드셰이킹의 종류

- 3-way 핸드셰이킹: 데이터를 주고받기 전에 상대방 컴퓨터와 세션을 수립하는 과정으로 요청과 응답을 총 3번 주고받는다.
- 4-way 핸드셰이킹: TCP 연결을 해제할 때 이뤄지는 과정으로 요청과 응답을 총 4번 주고받는다.

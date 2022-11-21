# 기능 구현 체크리스트 ☑️☐
☑️ 0. 시작 안내문구를 출력한다.
☑️ 1. inputView 객체에서 readBridgeSize() 메서드를 이용하여 사용자에게 다리의 길이를 받는다.
☑️ 2. BridgeRandomNumber객체에서 무작위로 0과 1를 저장하는 메서드를 구현한다
☑️ 3. BridgeMaker 객체에서 다리의 길이만큼(inputView.readBridgeSize()) 0과 1를 무작위로 받아 "U" 또는 "D"로 다리건너기 정답리스트를 만든다.
☑️ 4. inputView 객체에서 readMoving() 메서드를 이용하여 사용자에게 U 또는 D 값을 받는다.
☑️ 5. BridgeGame객체에서 move 메서드를 이용하여 사용자 값과 다리건너기 정답리스트가 같으면 정답리스트의 가장 맨 앞 요소가 삭제된다.
☐ 6. 결과 값을 표시한다.
☐ 7. 컴퓨터의 랜덤값과 사용자의 값이 같을때까지 반복한다.

☐ 8. 만약 값이 다르다면 inputView.readGameCommand에서 게임을 재시작할지 종료할지 사용자의 값을 입력받는다.
☐ 8-1. 게임을 재시작한다면, BridgeGame.retry()에서 이미 받은 BidgeMaker의 값과 4번의 기능을 다시 시작한다.
☐ 8-2. 게임을 종료한다면 최종 게임 결과(게임 성공 여부와 총 시도한 횟수)를 출력하고 게임을 종료한다.

☐ 9. 만약 값이 같다면 최종 게임 결과를 출력하고 게임을 종료한다.

# mvc패턴 지켜야 할 것.
1. model은 controller와 view에 의존하지 않는다.
2. view는 model에만 의존한다.
2-1. 조건) 사용자마다 다르게 보여줘야 할때만
2-2. 조건) 반드시 controller에서 받을 것
3. controller 내부에는 model과 view 의존한다.




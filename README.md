# CS-gym

## Contents

개발자가 필수적으로 알아야되는 필수 5대과목 자료구조, 알고리즘, 운영체제, 컴퓨터 네트워크, 자료구조를 정리한다.


## 궁금해 하지않으면 더 이상 깊어질 수 없다.

컨텍스트 스위치라는 게 있네 아 이거는 프로세스가 번갈아가면서 실행되는거구나라는 생각에서 멈출 수 있다.

근데 여기서 사고가 끊기면 더 이상 깊어질 수 없다.

왜 컨텍스트 스위치라는게 필요한데?
  - 프로세스를 번갈아가면서 실행시키기 위해
    + 왜 프로세스를 번갈아가면서 실행해야 되는데?
      - 해당 프로세스가 I/O 작업 등으로 인해 오랫동안 대기하는 상태면 자원의 낭비가 발생할 뿐더러, 하나의 프로세스만 실행되는 경우는 현대 컴퓨터 시스템에서 거의 없기 때문
        - I/O 작업은 왜 오래걸리는데?
          - blur blur ~~~

컨텍스트 스위치는 어떻게 이루어지지?
  - OS에서 PCB라는 자료구조를 두어 프로세스를 관리하는데 스케줄러에서 선정된 다음 수행 프로세스와 이전 프로세스를 교체할 때 이 PCB에 현재 수행 중이던 내용을 저장해놓는다.
    PCB에는 Program Counter, register 내의 값들, stack 영역의 주소 값 등등 여러가지 정보가 들어가게된다.
      - Program Counter는 뭔데?
      - stack안에는 어떤 정보가 들어가는데? 

등등 깊이는 끝이 없다.

## Output 활성화

단순 input만 하는 것이 아닌 스스로 설명할 수 있어야 된다. 그게 아니면 제대로 아는 것이 아니다. 아는척을 하는 것이다.

# CS-gym

<!--ts-->

- [CS-gym](#cs-gym)
  - [Contents](#contents)
  - [궁금해 하지않으면 더 이상 깊어질 수 없다](#궁금해-하지않으면-더-이상-깊어질-수-없다)
  - [Output 활성화](#output-활성화)
  - [정리 방식](#정리-방식)
  - [스크립트](#스크립트)
  - [license](#license)

<!-- Created by https://github.com/ekalinin/github-markdown-toc -->
<!-- Added by: sungminyou, at: 2022년 6월 13일 월요일 14시 06분 36초 KST -->

<!--te-->

## Contents

[자료구조](./Data%20Structure/)

[알고리즘](./Algorithm/)

[운영체제](./Operating%20System/)

[컴퓨터 네트워크](./Computer%20Network/)

[데이터베이스](./Database/)

## 궁금해 하지않으면 더 이상 깊어질 수 없다

컨텍스트 스위치라는 게 있네 아 이거는 프로세스가 번갈아가면서 실행되는거구나라는 생각에서 멈출 수 있다.

근데 여기서 사고가 끊기면 더 이상 깊어질 수 없다.

왜 컨텍스트 스위치라는게 필요한데?

- 프로세스를 번갈아가면서 실행시키기 위해
  - 왜 프로세스를 번갈아가면서 실행해야 되는데?
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

## 정리 방식

- 강의나 자료를 통해 개념을 정리하고, 전반적 정리가 끝나면 what, why, how 관점에서 분석하고 질문에 스스로 답할 수 있도록 정리 및 연습

- 강의나 자료는 신뢰할 만한지 항상 판단해야함

## 스크립트

```bash

$ yarn insert:toc # 목차 생성

$ yarn update:toc # 목차 갱신, 백업 파일 생성됨

$ yarn delete:backup # 백업 파일 제거

```

## License

[CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ko)

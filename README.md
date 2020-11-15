# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)


## 기능 요구 사항
* 기본적으로 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임이다.
* 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼, 같은 수가 전혀 없으면 포볼 또는 낫싱이란 힌트를 얻고, 그 힌트를 이용해서 먼저 상대방(컴퓨터)의 수를 맞추면 승리한다.
    * [예] 상대방(컴퓨터)의 수가 425일 때, 123을 제시한 경우 : 1 스트라이크, 456을 제시한 경우 : 1 스트라이크 1볼, 789를 제시한 경우 : 낫싱
* 위 숫자 야구게임에서 상대방의 역할을 컴퓨터가 한다. 컴퓨터는 1에서 9까지 서로 다른 임의의 수 3개를 선택한다. 게임 플레이어는 컴퓨터가 생각하고 있는 3개의 숫자를 입력하고, 컴퓨터는 입력한 숫자에 대한 결과를 출력한다.
* 이 같은 과정을 반복해 컴퓨터가 선택한 3개의 숫자를 모두 맞히면 게임이 종료된다. •게임을 종료한 후 게임을 다시 시작하거나 완전히 종료할 수 있다.


## 기능 명세서
- [X] 1. 1부터 9까지 서로 다른 수로 이루어진 랜덤한 3자리의 수를 만드는 기능
- [X] 2. 랜덤한 3자리의 수와 입력한 3자리의 수를 비교하여 결과를 나타내는 기능
    - 숫자와 자리가 모두 같을 경우 1 스트라이크
    - 숫자는 같지만, 자리가 다를 경우 1 볼
    - 3자리 숫자가 모두 다를 경우 낫싱
- [X] 3. 숫자를 맞추지 못하면 다시 입력받고 모두 맞추면 게임이 종료되는 기능
- [ ] 4. 게임이 종료되었을 때 게임을 다시 시작하거나 완전히 종료하는 기능
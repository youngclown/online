# Lupus-in-Tabula-On-line
# Toy Project

[웹마피아](https://namu.wiki/w/%EC%9B%B9%EB%A7%88%ED%94%BC%EC%95%84) 를 기리며 만들고자함.

게임 진행은 다음과 같이 진행됩니다.
----

1. 역할 배분: 모든 유저는 직업을 방 설정에서 정해진 포메이션에 따라 갖게 된다. 자신이 무슨 직업을 가졌는지는 다른 사람에게 알려지지 않는다.
2. 밤: 밤에는 스킬을 가진 유저가 스킬을 사용할 수 있다. 사회자를 제외한 누구도 말을 할 수 없다. 단 비밀채팅의 경우에는 밤과 상관없이 말할 수 있다.
3. 낮: 낮에는 밤에 스킬을 사용한 것에 대한 결과가 표시되게 된다. 그리고 늑대가 누구인지 토론을 하게 된다.
4. 1차 투표: 낮의 토론을 기초로 늑대일 것 같은 사람을 뽑는다. 가장 많은 표를 받은 사람이 변론을 하게 된다.
만약 동점표가 나오거나 투표를 아무도 하지 않았을 경우, 혹은 무투표가 가장 많을시에 변론 없이 밤으로 진행된다.
사회자 모드의 경우 사회자의 재량에 따라 투표를 생략하고 바로 밤으로 진행할 수 있다.
5. 변론: 가장 많은 표를 받은 사람이 변론을 할 수 있다. 자신이 늑대가 아님을 변론하면 된다.
6. 이의제기: 변론 이후 10초간의 이의제기 신청 시간이 있으며, 이 때 신청 순서대로 게임 설정의 변론시간만큼 이의제기를 할 수 있게 된다. 한명이라도 이의제 기를 신청한 경우 변론자는 재변론 시간을 가질 수 있고, 이후 최종 투표로 넘어가게 된다.(현웹마는 이의제기 기능이 사라졌다.)
7. 2차 투표: 변론을 한 사람을 사형시킬지를 찬반 투표를 통해 결정한다. 만약 찬성이 반대보다 많은 경우 해당 변론자는 죽게 되고, 반대가 찬성보다 많은 경우 죽지 않는다. 그리고 밤으로 진행된다.
단, 찬성과 반대의 투표수가 같을 경우 다시 (4)의 투표를 진행한다. 이것을 부결이라 하며, 한번 부결이 된 상태에서 또 부결이 났을때는 투표 없이 밤으로 진행된다.
8. 2에서 7을 반복하여 승리 조건을 만족할 때까지 게임을 진행한다.

승리 조건
---

- 늑대 팀: 늑대 팀의 생존수가 시민 팀의 생존수와 같거나 그보다 더 많을 경우
- 시민 팀: 늑대가 모두 사망한 경우, 또는 템플러와 늑대가 1 : 1 대치 상황일 때
- 쥐인간 팀: 늑대 팀 또는 시민팀의 승리조건을 만족하면서 쥐인간이 생존해 있을 때(최우선 조건)



H2 설정
---
[!이미지](/img/20180428_data_driver.PNG)

database 가 PUBLIC 으로 자동설정되어서 database를 추가해서 셋팅하지 않는한, PUBLIC 으로 데이터베이스를 설정해야함. (2019.04.28) 
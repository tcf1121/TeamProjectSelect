# TeamProjectSelect
 팀 프로젝트 구현게임 선정하기
## 송창렬
### 플레이어 구현 및 UI
플레이어 마우스 클릭 등에 대한 상호작용을 구현하고 UI를 담당하게 되었다.

만들 게임은 식물vs좀비 형식의 디펜스 게임이며,

기물을 원작과는 달리 오토체스류 형식의 게임처럼 살 수 있게 만들 생각이다.


### 아군 기물
기물은 기본 공격을 하거나 공격을 받으면 마나를 얻을 수 있고,
마나가 차면 특수 공격을 할 수 있게 만들 예정이다.
각 기물은 죽어도 그 스테이지에서만 죽는 판정이 되고 완전히 죽는 판정이 되지 않는다.
기물은 사거리를 가지며 사거리 안에 몬스터가 있어야 공격한다.

같은 단계의 같은 기물이 3개 있으면 다음 단계로 진화하고 총 3단계까지 진화 시킬 수 있다.
문제 없이 만들 수 있다면, 종족이 같을 경우 시너지가 나게 한다거나 하는 기능을 추가할 수도 있을 것 같다.

### 적 기물
총 20 스테이지로 구성할 예정이며, 5스테이지마다 보스 스테이지가 있다.
적의 경우도 그에 맞춰서 더 강해지게 설계할 예정이다.


### 상점
각 스테이지가 시작하기 전에 상점에서 기물을 살 수 있다.
총 5마리의 기물이 랜덤으로 나오며 마우스를 클릭하여 산다.
기물은 플레이어의 레벨에 따라 등급의 확률이 달라지고, 랜덤하게 나온다.
하지만 플레이어가 특정 기물을 3단계 즉 9마리를 얻었다면 더는 나오지 않으며, 살 수 없다.

### 플레이어
플레이어는 레벨과 돈을 가진다.
레벨은 스테이지를 클리어 하거나 돈을 사용하여 경험치를 얻어서 올릴 수 있다.
돈은 적 몬스터를 죽이면 얻을 수 있다. 하지만, 스테이지를 클리어 하지 못한다면, 돈의 일부를 잃게 된다.
기물을 마우스로 클릭하여 위치를 옮길 수 있다.


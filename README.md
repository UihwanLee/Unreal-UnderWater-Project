# Unreal-UnderWater-Project
 Unreal blueprint를 활용한 게임 프로젝트입니다.

  ## 게임 이름 
 > Under Water

![title](https://github.com/UihwanLee/Unreal-UnderWater-Project/assets/36596037/6c41e4af-b277-4a8d-9aa7-e9c0c420f614)

* [유튜브영상](https://youtu.be/BGmyWWnzkaE?si=nlJ4VTaVe5CLMBrO)

## 개발 컨셉

 * high_concept: 바다 속 환경에서 다양한 상호작용 및 재미 요소 첨가한 캐쥬얼 게임
 * 핵심 매커니즘: 바다에서 잠수하여 투척 석궁을 사용해 최대한 많은 물고기를 잡아 배고픔을 채우며 생존하자!

  
## 개발 주요 요소 

- 바다 속 환경에서의 Material 및 Lighting 기법 구현
- 바다 속 환경에서의 전투 시스템 구현 및 충돌처리 알고리즘 구현
- 캐릭터의 상태 스테이터스 UI 구현 및 RoundProcessBar 구현
- 2가지의 Scene 구성과 Game UI 구현

## 게임 시스템

> 전투 시스템

![8일차](https://github.com/UihwanLee/Unreal-UnderWater-Project/assets/36596037/3df62fa6-92c7-456c-90cf-57b443cf8639)
- 캐릭터는 깃창을 들고 있을 때 투척하여 적에게 공격을 가할 수 있다.
- 적과의 간단한 충돌처리를 통해 데미지를 가하고 데미지를 가하면 적이 사라진다.

> 애니메이션 시스템

![10일차](https://github.com/UihwanLee/Unreal-UnderWater-Project/assets/36596037/40763dd6-f6f6-4f91-a54b-c450bb8d17e9)
 - 애니메이션은 stateMachine에 따라 동작한다.
 - state 종류는 'GroundMoving'과 'Swiming'이 있다.
 - GroundMoving : 땅 위에 있을 때 행동하는 애미메이션으로 걷기 / 뛰기를 행동한다.
 - Swiming      : 물 속에 있을 때 행동하는 애미네시연으로 수영하기를 행동한다.

> 조작방법
- 플레이어 이동: Ground | RPG 카메라 모드
                Water  | FPS 카메라 모드


## 개발 일정

|주차|계획 내용|구체 계획|진행율|
|----|:----:|:----------:|:----:|
|1주차|Resource수집 & 게임 기반 완성|-WaterMap 생성 및 오브젝트 Material Bluepirnt 구현 |40%|
|2주차|Scene 관리 및 핵심 게임 시스템 구현|-|0%|
|3주차|디펜스 아군 유닛 구현|-아군을 소환하는 GUI 구현 & 아군 행동 AI 구현|0%|
||||20%|



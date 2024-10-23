# aster-command

(이 스크립트를 노리터 서버에 바칩니다)

아스터에 권한이 있는 플레이어가 사용할 수 있는 간단한 팀 유틸리티 커맨드입니다.

# 권한

기본적으로 아스터의 이장님과 서버장님만이 사용할 수 있..었는데, 테스트를 위해 제 닉네임도 권한 3인방에 들어가 있습니다.
추후 커맨드가 완료됐을시 d5mu는 권한에 삭제될 수 있습니다.

# 사용 방법

커맨드는 모두 /aster로 상호작용할 수 있습니다.

## tp


**/aster tp (플레이어)**

---

(플레이어) 부분에 아스터 멤버의 닉네임을 적으면 그 위치로 순간이동합니다.

플레이어를 적지 않고 공백으로 둘 시, 해당 명령어의 사용 방법을 짧게 안내합니다.

## reject


**/aster reject (플레이어) (기각 사유)**

---

해당하는 아스터 멤버의 의견을 기각하고, 1 대미지를 주어 맴매합니다. 기각당한 플레이어에게 폭발 사운드가 재생됩니다.

기각 사유를 선택적으로 적을 수 있습니다. 기각 사유에 원하는 문장을 적으면, 기각당한 플레이어의 "기각!" 타이틀 밑에 해당 사유가 같이 보이게 됩니다.

기각 사유에 **explosive reject**를 적을 시, 일반적인 기각이 아닌 매우 폭발적인 기각을 선사하여 20 대미지를 줍니다. 기각을 받은 플레이어는 상처를 받아 10초간 나약함의 효과를 부여받고, 그럴만한 기각 사유에 20초 동안 채팅을 보낼 수 없습니다.

서버장을 기각할 시 큰일납니다.




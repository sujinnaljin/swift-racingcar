## 자동차 경주 미션 저장소
### Effective Swift
NEXTSTEP with yagom-academy



# 1주차

## 4단계 - 자동차 경주(우승자)

### 기능 요구 사항

- 각 자동차에 이름을 부여할 수 있습니다. 자동차 이름은 5자를 초과할 수 없습니다.
- 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력합니다.
- 자동차 이름은 쉼표(,)를 기준으로 구분합니다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려줍니다. 우승자는 한 명 이상일 수 있습니다.

### 구현할 기능 목록

- [x] 자동차 이름 입력 받기
- [x] 입력받은 자동차 이름 "," 기준으로 쪼개기
- [x] 쪼갠 자동차 이름 중 하나라도 5 글자 초과하면 throw
- [x] Car 객체에 name property 추가 (+ init 함수 수정)
- [x] Result View 에서 print 할 때 car.name 같이 출력
- [x] 마지막 record 에서 car.position 의 max 값 구한 후에, 마지막 position 이 max 값과 일치하는 모든 car 객체 찾아서 최종 우승자로서 name print


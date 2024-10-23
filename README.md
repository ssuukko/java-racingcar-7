# java-racingcar-precourse
## 기능 구현 목록

- [ ] 자동차 클래스(Car) 구현
  - 자동차의 이름과 이동 상태를 저장하는 클래스를 구현합니다.

- [ ] 전진 로직 구현
  - 0~9 사이의 무작위 숫자를 생성하는 로직을 추가합니다.
  - 숫자가 4 이상일 경우 자동차가 전진하도록 구현합니다.

- [ ] 사용자 입력 처리
  - 자동차 이름과 시도 횟수를 입력받는 기능을 구현합니다.
  - 이름이 쉼표(,)로 구분되며, 5자 이하 조건을 충족하는지 확인합니다.

- [ ] 경주 로직 구현
  - 자동차 이름이 5자 이하인지 검증하는 로직을 추가합니다.
  - 입력받은 횟수만큼 자동차가 전진 또는 멈추도록 경주를 반복합니다.
  - 매 차수마다 각 자동차의 상태를 출력합니다.

- [ ] 우승자 판별 로직 구현
  - 경주가 끝난 후 가장 많이 전진한 자동차(또는 공동 우승자)를 판별합니다.
  - 우승자를 출력하는 기능을 구현합니다.

- [ ] 결과 출력
  - 차수별로 각 자동차의 상태를 출력합니다.
  - 최종 우승자를 출력합니다.

- [ ] 예외 처리
  - 입력값이 잘못된 경우 `IllegalArgumentException`을 발생시키고 프로그램을 종료하는 로직을 추가합니다.

- [ ] 테스트 및 디버깅
  - 각 기능이 정상적으로 동작하는지 테스트하고 오류를 수정합니다.
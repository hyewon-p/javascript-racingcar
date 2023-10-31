# 기능 목록

## 입력 요구 사항

- 경주할 자동차의 이름(쉼표 기준으로 구분)
    - *경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)*
- 시도할 횟수(이동 횟수)
    - *시도할 횟수는 몇 회인가요?*

## 출력 요구 사항
- 각 차수별 실행 결과
    - *실행 결과*
    - *??? : --*
- 경주 게임 결과(우승자)
    - *최종 우승자 : ??*
    - 우승자가 여러 명일 경우 쉼표로 구분한다.

## 자동차 기능 요구 사항
- 주어진 횟수 동안 전진 또는 정지한다.
- 전진하는 조건: 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우

## 에러 관련 사항 
- 사용자가 잘못된 값을 입력한 경우 throw문을 사용해 "[ERROR]"로 시작하는 메시지를 가지는 예외를 발생시킨 후, 애플리케이션을 종료한다.
- 이름은 5자 이하여야 한다.
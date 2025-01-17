### 구현 기능 목록

- 로또 구입 금액 입력받기
- 발행한 로또 수량 및 번호 출력하기
- 당첨 번호 입력받기
- 보너스 번호 입력받기
- 당첨 내역 출력하기
- 수익률 출력하기

### 기능별 세부 사항

1.로또 구입 금액 입력받기

- 로또 구입 금액을 1,000원 단위로 입력받기
  값이 숫자가 아니거나 1,000원으로 나누어 떨어지지 않는 경우 throw문으로 예외 처리

  2.발행한 로또 수량 및 번호 출력하기

- 겹치지 않는 1~45의 숫자 6개를 오름차순으로 정렬하여 보여주기
- 구매한 개수만큼 로또 번호 내역 출력하기

  3.당첨 번호 입력받기

- 쉼표를 기준으로 구분하여 겹치치 않는 숫자 6개 입력받기
- 중복된 숫자가 있거나 번호가 1~45의 숫자가 아닌 경우 throw문으로 예외 처리

  4.보너스 번호 입력받기

- 당첨 번호 6개와 겹치지 않는 1~45의 숫자 1개 입력받기
- 당첨 번호와 겹치거나 1~45의 숫자가 아닌 경우 throw문으로 예외 처리

  5.당첨 내역 출력하기

- 당첨 내역을 당첨 개수와 함께 출력하기
- 3개 일치 (5,000원) - 1개
- 4개 일치 (50,000원) - 0개
- 5개 일치 (1,500,000원) - 0개
- 5개 일치, 보너스 볼 일치 (30,000,000원) - 0개
- 6개 일치 (2,000,000,000원) - 0개

  6.수익률 출력하기

- 수익률을 소수점 둘째 자리에서 반올림하여 출력하기

### 프로그래밍 요구 사항

- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
- 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 - 메서드)를 분리하면 된다.
- 함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 만들어라.
- Jest를 이용하여 본인이 정리한 기능 목록이 정상 동작함을 테스트 코드로 확인한다.
- 함수(또는 메서드)의 길이가 15라인을 넘어가지 않도록 구현한다.
  else를 지양한다.
- 도메인 로직에 단위 테스트를 구현해야 한다. 단, UI(Console.readLineAsync, Console.print) 로직에 대한 단위 테스트는 제외한다.
- 핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.

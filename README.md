# 🥇 로또 (우아한 프리코스 3차 과제)

## ➡️ 기능 목록

- 로또 구입 금액 입력 받기
- 당첨 번호 입력 받기
- 보너스 번호 입력 받기
- 발행한 로또 수량 및 로또 번호 리스트를 오름차순으로 출력
- 일치한 숫자의 개수를 기반으로 당첨 내역을 출력
- 총 수익률을 소수점 둘째 자리에서 반올림하여 출력
- ❗1000원으로 나누어 떨어지지 않으면 예외 처리
- ❗중복된 숫자 입력 시 예외 처리

## ➡️ 클래스

### ➡️ Lotto

- 로또 배열 저장
- 로또 배열 검증 메서드
- 오름차순 정렬 메서드
- 보너스 번호 입력 및 추가, 출력 메서드

### ➡️ PurchaseAmount

- 구입금액 검증
- 로또 구매 개수 반환 및 출력 메서드

## ➡️ 주의 사항

- indent depth는 2까지만 허용
- 3항 연산자 사용 X
- 함수는 최대한 작게
- Jest를 이용한 테스트 코드 작성
- 함수의 길이가 15라인 넘지 않게 할 것
- else 지양
- LottoTest를 참고해 단위 테스트 작성
- 제공된 Lotto 클래스 사용해서 구현
- numbers 이외의 필드 추가 X
- numbers의 접근 제어자인 #은 변경 불가
- Lotto 패키지 변경 가능

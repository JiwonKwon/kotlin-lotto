# kotlin-lotto

## 문자열 덧셈 계산기 
### 기능 목록
- [x] 문자열을 입력받는다
- [x] 입력받은 문자열을 쉼표(,)와 콜론(:)을 기준으로 분리한다
- [x] 문자열 계산기에 , : 이외의 문자가 들어올 경우 RuntimeException을 발생시킨다
- [x] 문자열 계산기에 음수를 전달할 경우 RuntimeException을 발생시킨다
- [x] 문자열 계산기에 // \n(줄바꿈) 형식으로 커스텀 구분자를 지정할 수 있다
- [x] 커스텀구분자가 있어도 커스텀구분자 이외의 문자가 들어올 경우 RuntimeException을 발생시킨다
- [x] 문자열 계산기에 커스텀 구분자를 지정할 경우 커스텀 구분자를 기준으로 분리한다

## 로또(자동)
### 기능 목록
- [x] 로또 구입금액을 입력받는다
- [x] 로또 1장의 가격은 1000원이다
- [x] 로또 구입금액 입력 시 구매수량이 정해진다
- [x] 로또 구입금액 입력 시 구매수량이 정해지면 구매수량을 출력한다
- [x] 로또 구입금액 입력 시 구매수량이 정해지면 구매수량만큼 로또를 발급하고 출력한다
- [x] 로또 1장은 6개의 숫자를 가진다
- [x] 로또 1장의 숫자는 1~45의 숫자이다
- [x] 로또 1장의 숫자는 중복되지 않는다
- [x] 로또 1장의 숫자는 오름차순으로 정렬되어있다
- [x] 지난 주 당첨 번호를 입력받는다
- [x] 지난 주 당첨 번호는 6개의 숫자이다
- [x] 지난 주 당첨 번호는 1~45의 숫자이다
- [x] 지난 주 당첨 번호는 중복되지 않는다
- [x] 지난 주 당첨번호가 입력되면 로또 별 일치하는 숫자가 몇개인지 계산한다
- [ ] 당첨 통계는 1등부터 4등까지 출력한다
- [ ] 4등: 3개 일치 (5000원), 3등: 4개 일치 (50000원), 2등: 5개 일치 (1500000원), 1등: 6개 일치 (2000000000원)
- [ ] 지난 주 당첨 번호가 입력되면 당첨 통계를 출력한다
- [x] 당첨 통계는 로또 구입금액과 당첨금을 비교하여 수익률을 계산한다
- [x] 수익률은 총 수익금 / 총 구입금액 으로 계산한다
- [ ] 총 수익률을 출력한다
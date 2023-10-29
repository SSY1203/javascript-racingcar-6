# 🚖 미션 - 자동차 경주

- [ ] 경주할 자동차 이름들을 입력 받는다.
- [ ] 자동차 이름의 길이가 0인지 검증한다.
- [ ] 입력된 자동차 이름에 쉼표(,)가 연달아 나오는지 검증한다.
- [ ] 입력된 자동차 이름에 쉼표(,)가 없는지 검증한다.
- [ ] 입력된 각 자동차 이름이 5자 이하인지 검증한다.
- [ ] 입력 받은 자동차 이름들을 저장한다.
- [ ] 시도할 횟수를 입력 받는다.
- [ ] 시도 횟수가 음수 및 0이 아닌지, 숫자인지 검증한다.
- [ ] 입력 받은 시도 횟수를 저장한다.
- [ ] "실행 결과" 문구를 출력한다.
- [ ] 각 시도 마다 각 자동차들에게 0에서 9 사이의 무작위 값을 뽑아 4 이상일 경우, 해당 자동차에 해당하는 변수에 문자열 '-'을 추가한다.
- [ ] 자동차들에 대해 전진 결과를 각 시도마다 출력한다.
- [ ] 모든 시도가 끝나면 최종 우승자를 출력한다.
- [ ] 우승자가 2명 이상일 경우, 쉼표(,)로 구분하여 출력한다.

### Cars(Model)

- 자동차 이름 배열 생성 및 get, set
- 자동차 전진 횟수 배열 생성 및 get, set

### View

##### InputView

- 경주할 자동차 이름들을 입력 받는다.
- 자동차 이름의 길이가 0인지 검증한다.
- 입력된 자동차 이름에 쉼표(,)가 연달아 나오는지 검증한다.
- 입력된 자동차 이름에 쉼표(,)가 없는지 검증한다.
- 입력된 각 자동차 이름이 5자 이하인지 검증한다.

- 시도할 횟수를 입력 받는다.
- 시도 횟수가 음수 및 0이 아닌지, 숫자인지 검증한다.

##### OutputView

- "실행 결과" 문구를 출력한다.
- 자동차들에 대해 전진 결과를 각 시도마다 출력한다.
- 모든 시도가 끝나면 최종 우승자를 출력한다.
- 우승자가 2명 이상일 경우, 쉼표(,)로 구분하여 출력한다.

### CarRacingReferee(Controller)

- 입력 받은 자동차 이름들을 저장한다.
- 입력 받은 시도 횟수를 저장한다.

- 각 시도 마다 각 자동차들에게 0에서 9 사이의 무작위 값을 뽑아 4 이상일 경우, 해당 자동차에 해당하는 변수에 문자열 '-'을 추가한다.

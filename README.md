# 🧮 Calculator

### ▶️ HTML / CSS / JavaScript 활용 연습 Part01
### : 다양한 기능을 넣은 계산기 구현하기
### DEMO : https://d-charlie-kim.github.io/Calculator/

<hr>

### 🔽 기능 구현 목록


#### /* 기본 연산 기능 */
- [x] 덧셈 버튼으로 덧셈 계산
- [x] 뺄셈 버튼으로 뺄셈 계산
- [x] 곱셈 버튼으로 곱셈 계산
- [x] 나눗셈 버튼으로 나눗셈 계산
- [x] '%' 퍼센트 버튼으로 퍼센트 값 계산
- [x] '+/-' 음수 양수 전환 버튼으로 음수 양수 전환
- [x] 'AC' All Clear 버튼으로 reset하기
- [x] '=' Eqaul 버튼으로 수식 결과 출력하기
- [ ] '.' Dot 버튼으로 소숫점 입력
- [X] 처음 실행 시 기본값 '0'으로 시작
- [ ] '.' Dot 버튼 한번만 입력 받기

#### /* History (지난 수식 기록) 기능 */
- [x] 숫자 입력 이후에 연산자 입력 시 현재 수식 표현
- [x] 'AC'버튼 혹은 '=' Equal 버튼 입력시 출력 초기화
- [x] '숫자 + 연산자' 입력 후 다시 '연산자' 입력 시 연산자가 변경되는 부분을 제대로 출력
- [x] 계산기 표시 문자 중 곱셈, 나눗셈 연산자를 (* / 아니고) 적절하게 출력

#### /* 화면 표시 (HTML / CSS) */
- [ ] 숫자가 계산기를 넘어가면 적절하게 두줄 처리
- [ ] 배치와 버튼 크기 적당한 비율로 조정
- [ ] (반응형) 화면 크기 줄이고 늘였을 때 적절히 반응
- [ ] 가로 모드 지원
- [ ] 가로 모드 시, 연산자 추가 가능하게 공간 확보
- [ ] 연산자 클릭 시, 연산자 색상 반전
- [ ] 버튼 클릭 시 , 눌리는 듯한 모션 추가
- [ ] 버튼에 마우스 올리면 해당 버튼 활성화 하는 듯한 모션

#### /* 추가 기능 */
- [x] '숫자 + 연산자' 입력 후 다시 '연산자' 입력 시 연산자가 변경되는 부분
- [x] 불완전한 수식 ('숫자'만 혹은 '숫자 + 연산자'만) 이후에 '=' Equal 버튼 입력시 숫자 정상 출력
- [x] 현재 숫자가 '0'인 상태에서 '0' 입력 시 입력을 막는 기능
- [ ] 아이폰과 동일하게 처음 숫자 9자리만 입력 받고, 그 이상은 무시
- [ ] 숫자 화면 출력 시 3자리 마다 ','로 구분
- [ ] 수식 계산이 한번 종료된 이후 '=' Equalq 버튼 입력 시 이전 연산 기억해서 계속 연산해주기
- [ ] 사칙연산 우선 순위 고려해서 계산하기
- [ ] 숫자 입력 시 'AC' All Clear 버튼 -> 'C' 버튼으로 전환
- [ ] 'C' Clear 버튼 클릭 시 현재 연산 과정 유지된 상태로, 숫자만 새로 입력 받기

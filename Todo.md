# 프로그램 실행 흐름
1. 구입금액 입력
   - 1000원으로 나누어 떨어지지 않으면 예외 발생
2. 구입한 로또 개수만큼 random으로 6개씩 숫자 출력
   - 오름차순으로 출력
   - 1부터 45 사이의 random숫자
   - 한 로또에는 중복되는 숫자가 있으면 안된다.
3. 당첨 번호 6개를 내가 입력
   - 쉼표로 구분할 수 있도록 입력
   - 중복되지 않는 6개의 숫자여야 함
   - 중복되는 수가 존재 -> 예외 발생
   - 6개 미만, 6개 초과인 수 입력 -> 예외 발생
4. 보너스 번호 입력
   - 이 보너스 번호는 당첨번호 6개와 중복되면 안되는 수인가??
5. 당첨 통계 출력
   - n개 일치 (당첨 금액) - 당첨번호와 숫자가 3개 일치하는 로또의 개수
   이렇게 n=3~6개까지 출력
   - 총 수익률 구하기 : (당첨 금액)/(구입 금액) * 100

```
구입금액을 입력해 주세요.
8000

8개를 구매했습니다.
[8, 21, 23, 41, 42, 43] 
[3, 5, 11, 16, 32, 38] 
[7, 11, 16, 35, 36, 44] 
[1, 8, 11, 31, 41, 42] 
[13, 14, 16, 38, 42, 45] 
[7, 11, 30, 40, 42, 43] 
[2, 13, 22, 32, 38, 45] 
[1, 3, 5, 14, 22, 45]

당첨 번호를 입력해 주세요.
1,2,3,4,5,6

보너스 번호를 입력해 주세요.
7

당첨 통계
---
3개 일치 (5,000원) - 1개
4개 일치 (50,000원) - 0개
5개 일치 (1,500,000원) - 0개
5개 일치, 보너스 볼 일치 (30,000,000원) - 0개
6개 일치 (2,000,000,000원) - 0개
총 수익률은 62.5%입니다.
```
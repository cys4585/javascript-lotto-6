# 3주 차 미션: 로또

## 미션 목표

- [ ] **클래스(객체)를 분리하는 연습**
- [ ] **도메인 로직에 대한 단위 테스트를 작성하는 연습**

---

## 프로세스

1. 애플리케이션 실행
2. 구입 금액 입력
3. 입력한 금액만큼 로또 구매
4. 구입한 로또 번호 출력
5. 로또 당첨 번호 입력
6. 보너스 번호 입력
7. 로또 당첨 여부 확인
8. 당첨 통계 계산
9. 당첨 통계 출력
10. 애플리케이션 종료

---

## 기능 목록

#### 로또 인터페이스

##### 입력

1. [ ] 구입할 금액 입력
   - [ ] 검사: 숫자로 구성
2. [ ] 당첨 번호 입력
   - [ ] 검사: 숫자와 콤마(`,`)로 구성
3. [ ] 보너스 번호 입력
   - [ ] 검사: 숫자로 구성

##### 출력

1. [ ] 구입한 로또 번호 출력
2. [ ] 로또 당첨 통계 출력

#### 로또 매니저

2. [ ] 로또 발급
   - 구입한 금액에 맞게 로또 발급
   - [ ] 검사: 구입한 금액이 로또 장당 가격으로 나누어 떨어짐
3. [ ] 로또 당첨 여부 확인
   - 3개 일치, 4개 일치, 5개 일치, 5개 일치 + 보너스 일치, 6개 일치
4. [ ] 로또 당첨 통계 계산
   - 당첨된 로또 카운팅
   - 수익률 계산

#### 로또

1. [ ] 로또 생성
   - [ ] 검사: 숫자 개수 (6개)
   - [ ] 검사: 1 ~ 45 범위
   - [ ] 검사: 중복 번호
2. [ ] 로또 번호 반환

#### 당첨 로또

1. [ ] 로또 유효성 검사
   - [ ] 검사: 숫자 개수 (6개, 1개)
   - [ ] 검사: 1 ~ 45 범위
   - [ ] 검사: 중복 번호
2. [ ] 로또 번호 반환
3. [ ] 보너스 번호 반환
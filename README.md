# JS-Competitive-Programming-Notes

# 알고리즘 설계 Tip
<img width="637" alt="스크린샷 2024-08-16 오후 3 43 25" src="https://github.com/user-attachments/assets/5a6c33c4-bbf4-4a43-9a3e-af1981219d45">

### 요구사항에 따라 적절한 알고리즘 설계하기
<img width="625" alt="스크린샷 2024-08-16 오후 3 44 26" src="https://github.com/user-attachments/assets/201fdb7c-6dcf-469a-9923-1f44490cc2f9">


---

# 시간 복잡도

- 알고리즘의 성능을 나타내는 척도
- 특정한 크기의 입력에 대하여 알고리즘의 수행 시간 분석하기 위해 사용한다.
- 동일한 기능을 수행하는 알고리즘이 있다면, 일반적으로 **복잡도가 낮을수록 우수**하다.

## 빅오 표기법(Big-O Notation)
<img width="625" alt="스크린샷 2024-08-16 오후 3 44 53" src="https://github.com/user-attachments/assets/85d1866f-9ecd-419c-aadb-121f05d28dba">


## 예시 1
<img width="625" alt="스크린샷 2024-08-16 오후 3 45 23" src="https://github.com/user-attachments/assets/809c5919-416e-4fc8-9823-b8410d530c73">
</br>
더하기 연산이 5번 수행됨 → 수행시간은 데이터의 개수 N에 비례!

## 예시 2
<img width="625" alt="스크린샷 2024-08-16 오후 3 45 50" src="https://github.com/user-attachments/assets/7dacfcb6-755d-4519-8737-b31814936d2a">
</br>
곱셈 연산이 5*5로 수행됨 → 수행시간은 데이터의 개수가 N제곱…

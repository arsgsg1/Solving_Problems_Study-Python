# Solving Problems Study - Python

- 코딩테스트를 대비하기 위해 문제를 풀고 주 2회 코드리뷰를 하는 스터디입니다.
- 언어 : Python
- 참고 사이트 : [백준](https://www.acmicpc.net/) / [프로그래머스](https://programmers.co.kr/) / [Leetcode](https://leetcode.com/explore/) / [SW Expert Academy](https://swexpertacademy.com/)

<br>
<p>
</p>

## ✅ 스터디 방식

### 1. 매 주 아래 순서대로 5문제 제출 (금요일 오전 8시 전)
  
|순서|이름(git_id)|
|---|------|
|1|전소현(sohyeonnn)|
|2|김도윤(dyoon1635)|
|3|김경민(jjongguet4u)|
|4|오지애(ohjiae)|
|5|윤좌홍(arsgsg1)|
|6|이홍덕(doggydeok2)|
|---------|
|8월 이후|이호진(ili0820)|
|8월 이후|이은경(stat-eklee)|


<br>
<p>
</p>  

### 2. 문제 수, 난이도

> (필수) **`보통`** 1문제, **`어려움`** 2문제 / (선택) **`보통`** 1문제, **`어려움`** 1문제<p>

- 매 주 **화요일 오후 9시 전**까지 (필수) 문제 답 제출 (<- 출석 기준. 시도 흔적이라도 올려야함)
- 깃허브로 Pull requests가 9시 전에 되어야 함

<p>
</p>   
  
#### 난이도 기준 (절대적 기준 X 자기 재량껏)
- **`보통`** : 백준 = 실버 1 ~ 골드 4
- **`어려움`** : 백준 = 골드 3 이상
- 프로그래머스는 재량껏 레벨2 이상 난이도 매겨주세요. 좋은 문제는 레벨 1도 가능

<br>
<p>
</p>  
  
### 3. 주 1회 **오후 9시** 코드 리뷰

- [전원] 화요일 오후 9시 전까지 문제푼 파이썬 파일 깃허브 업로드+PR

- [문제 제출자] 수요일 오전 9시 전까지 5문제 제출 


<br>
<p>
</p>  

### 4. 보증금 제도
중간 이탈로 인해 스터디 분위기가 망가지는 것을 방지하기 위해, 보증금제를 진행합니다.

> 보증금 : 총 2만원
> 1) '참여 보증금' 1만원
> 2) '벌금 차감용' 1만원

- `참여 보증금` : 한 달동안 참여 조건의 보증금. 중간 이탈시 돌려주지 않음

- `벌금 차감용` : 
  - 1회차 불참 = **1000원** 차감
  - 2회차 불참 = **1500원** 차감 (가중치 부여)
  - => 주 2회 연속 불참시 **총 2500원** 차감
  - 지속된 벌금 차감으로 인하여 10000원이 다 소진되었을 경우, 추가로 만원 입금해 다시 시작.

- **매 달 말일, 다음달 참여 여부를 여쭤봅니다.** (이 때 외에 탈퇴하는 분들 = '중간이탈자')
  - 이 때 스터디 탈퇴시 '참여 보증금'을 돌려주고, 중간 이탈시 만원은 안돌려드립니다.
  - 월말 탈퇴자 : `보증금 2만원-벌금` 돌려줌
  - 중간이탈자 : `1만원-벌금`만 돌려줌 
 
- 돌려드리고 남은 금액 > 0 이면, N분의 1로 나누어 가집니다 (벌금자 제외 나머지 인원 = N)
  - 벌금 정산 타이밍 : 누군가 탈퇴 혹은 벌금을 채워야하는 등의 업데이트 시점에 정산

<br>
<p>
</p>



## ✅ 파일 및 폴더 구조

- 파일 이름 규칙 : [문제출처]문제번호-문제이름.py _(문제 번호 없으면 기재 X. 문제 이름 내에 공백이 있다면 \_ 로 구분)_
  - 예시 : `[BOJ]1931-회의실_배정.py`

- .py 파일은 **본인 폴더**에 넣기 (자기폴더 / 파이썬 파일)
  - 예시 : 문제 푼 python 파일 -> `ohjiae` / `[BOJ]1931-회의실_배정.py`

<br>
<p>
</p>

## ✅ Commit Message Convention
### 난이도 [이슈번호1] 문제출처1 - 문제번호

- 난이도 이모티콘 : 🔵 보통 / 🔴 어려움 
- 문제 출처 : BOJ = 백준 / PRG = 프로그래머스 / LCD = 릿코드 (그외 사이트도 영문 세글자로 명명)
- 커밋 예시 : 
  - `🔵 [#23] BOJ-1020`
  - `🔴 [#25] PRG-40230`

- **문제는 1문제씩 따로 따로 커밋해주세요**

<br>
<p>
</p>

## ✅ PR Convention
### 해당 요일 [이슈번호1][이슈번호2][이슈번호3]

- 요일 이모티콘 : 🔥 화 / 🌳 목
- PR 예시 :
  - 하루치만 올릴 때 - `🔥 [#23][#24][#26]`
  - 이틀치 모두 - `🔥🌳 [#23][#24][#25][#26][#27]`

<br>
<p>
</p>

## ✅ Issue Convention (문제 출제자)
### 이슈 제목 : [문제출처] 문제번호 - 문제이름
### 이슈 내용 : 해당문제 링크
- 예시
- 이슈 제목 : `[백준] 1931 - 회의실 배정`  / 이슈 내용 : 해당 문제 링크
- 이슈 제목 : `[프로그래머스] 42682 - 체육복` / 이슈 내용 : 해당 문제 링크
  - 프로그래머스는 보통 url에 문제번호 있음

<p>
</p>

### 태그 **4개** 달아주세요
태그는 대부분 생성되어 있으나, 없을 시 생성해서 추가해주세요 (영문 세글자)

- 문제출처 : 백준 = `BOJ`, 프로그래머스 = `PRG`, 릿코드 = `LCD`, 삼성 SWEA = `SEA`
- 난이도 : 보통 = `Normal`, 어려움 = `Hard`
- 해당요일 : `화요일`, `목요일`
- 선택, 필수 여부 : `선택`, `필수`

<br>
- 예시 사진<br>

![image](https://user-images.githubusercontent.com/77822999/173480107-8f302904-f688-4d7b-8acc-573249695559.png)

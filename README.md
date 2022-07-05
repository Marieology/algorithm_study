# 코딩 문제 풀이 스터디 규칙
One week, One meeting, One problem, One to One coding test study

## 📌 문제풀이 문서와 소스코드 저장하는 규칙 
- 자세한 형식은 `./예시_githubID` 폴더를 참고 해봅니다.
- 자기 폴더 내에 문제 하나당 `[출처]_문제이름`형식의 이름을 가지는 폴더를 만듭니다.
- 문제 폴더 내에는 문제 풀이를 글로 설명하는 README.md 파일과 소스코드를 올립니다.
- 소스코드 파일명은 자유입니다.
- 폴더명 또는 소스코드 파일명에 콜론 ":" 안됩니다

<br />
<br />

## 📌 commit 규칙
- 문제 하나당 1 commit
- commit 메세지: [문제 출처(플랫폼)] 문제이름 / 난이도 / 걸린시간 
- description: 문제 주소 (option)
- 터미널에서 작성법: 
```
git commit -m "[BOJ] Hello World / 브론즈5 / 1분" -m "https://www.acmicpc.net/problem/2557"
```
- 플랫폼 작성법 통일: 
  * [BOJ] - 백준 
  * [PGS] - 프로그래머스
  * [LTC] - 리트코드
  * [CFS] - 코드포스
  * [SEA] - 삼성SW Expert Academy
  * [ETC] - 그외

<br />
<br />

## 📌 PR 규칙
- PR 제목: 이름 / 주차 / 몇 문제
-  ```jihun / 6월 1주차 / 4문제 ```
-  comment는 자유이나 가능하다면, 이번주에 풀었던 문제의 알고리즘 분류가 어떻게 되는지, <br> 어떤 문제가 어려웠는지 회고를 작성한다면 개인에게도 도움되고 다른 코드 리뷰어가 참고하기 좋을 것 같습니다 :)


<br />
<br />

## 📌 (option)코드리뷰 규칙
- PR에서 코드리뷰를 한다.
- 전체 코드 흐름을 파악한 뒤, 이 분이 어떻게 풀었을까 이해를 한 후 
- 의견제시
  -   잘했다고 생각하는 부분
  -   이렇게 하면 더 좋을 것 같다고 생각하는 부분
  -   왜 이렇게 풀었는지 궁금한 부분
  -   또 다른 풀이 방식 제시
- 코드의 일부분에다 코드리뷰를 해도 되고 전체 코드 밑 or PR 하나 밑에다 코멘트 작성으로 리뷰를 해도 됩니다.

<br />
<br />

> 참고한 repo: [https://github.com/ellynhan/challenge100-codingtest-study](https://github.com/ellynhan/challenge100-codingtest-study)

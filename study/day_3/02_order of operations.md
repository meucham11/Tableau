ORDER OF OPERATIONS : 계산과 필터의 작동 순서.

<img width="352" alt="1" src="https://user-images.githubusercontent.com/34879309/88455471-7cb4a180-ceb0-11ea-939b-f9d06d571f2e.png">

<BR/>
이미지 출처 :https://community.tableau.com/s/idea/0874T000000H9zbQAC/detail

----


```
이동평균 기능을 이용할 수가 있고 계산 필드 WINDOW함수를 이용해서 만들 수 있고 선택은 자유

여기서 볼 점은 필터와 테이블 계산중 ORDER DATE를(차원을) 필터에 올려서 날짜를 선택하게 되면 필터가 먼저 적용이 되어
작업 순서가 어떻든 상관없이 필터링 된 후에 테이블 계산이 일어나게 된다.
그래서 LAST 함수를(테이블 계산 필터를) 이용한다.
```
<img width="1165" alt="2" src="https://user-images.githubusercontent.com/34879309/88456169-79bcaf80-ceb6-11ea-9a9c-9bd42e9dafac.PNG">

<img width="1176" alt="3" src="https://user-images.githubusercontent.com/34879309/88456265-44fd2800-ceb7-11ea-8ee8-e992e3290405.PNG">

<br />

----

```
위와는 다르게 날짜는 last를 사용해서 풀었지만 문자열을 기준으로 필터링 해야 한다면?

변수를 그대로 필터링 하여 표본을 몇개 뽑는다면 랭크가 1순위부터 초기화 된 상태로 나열된다.
랜덤으로 뽑았을 때 기존 랭크를 그대로 가지고 오게 하고자 한다.
```

img

<br/>

----

img
```

```

vlod에 대해서 배워보자
Include  Exclude  Fixed

Fixed가 유연성이 있고 Include와 Exclude보다 많이 쓰인다.
Include와 Exclude
vlod에 포함되지 않는 차원을 이용할 수 있다는 점!


----
# Include lod

```
VLOD에서 주로 상위(얕은)레벨을 포함한다.
```

<img width="989" alt="1" src="https://user-images.githubusercontent.com/34879309/88450187-19af1480-ce88-11ea-924b-872112f0e89f.PNG">



<br/>

----

# Exclude lod

```
VLOD 기준에서 지우고 싶은 차원을 지운후계산
```

<img width="1113" alt="2" src="https://user-images.githubusercontent.com/34879309/88450189-1ae04180-ce88-11ea-81db-0cb85adb2558.PNG">

<br/>

----

```
```

<img width="1112" alt="3" src="https://user-images.githubusercontent.com/34879309/88450191-1b78d800-ce88-11ea-920e-65dc2711b288.PNG">

<br/>

----

## fixed lod
```
1차적으로 fixed lod에서 계산이 이루어지고
2차적으로 vlod에 맞추어 재집계가 이루어 진다.

이때는 무조건 사용해야만 한다
- 전체 데이터셋 범위에서 집계값을 잡을 때
- 날짜 필드를 활용할 때(최근 3개월, 올해, 지난 주 등)
- 필터의 영향을 받지 않는 값을 만들어야 할 때
```
<img width="1104" alt="4" src="https://user-images.githubusercontent.com/34879309/88451224-0142f800-ce90-11ea-99d4-a0459d19c8ba.PNG">

<br/>

<img width="1111" alt="6" src="https://user-images.githubusercontent.com/34879309/88451750-4701bf80-ce94-11ea-8a40-c1ef58a0629f.PNG">


<img width="1112" alt="7" src="https://user-images.githubusercontent.com/34879309/88451749-45d09280-ce94-11ea-9ce8-03b9efc305df.PNG">

<br/>

----


```

```
img


<br/>

----


```

```

img

<br/>

----

img
```

```




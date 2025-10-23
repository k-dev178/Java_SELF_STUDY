# 변수
'하나의 값'을 저장하기 위한 '저장 공간'

## 선언
```java
int age;
```

## 쓰기(Write)
```java
age = 10;

int age = 10; #선언과 동시에 Write 할 수 있다.
```

변수에 처음으로 값을 저장하는 행위를 초기화(initialization)이라고 한다.

## 읽기(Read)
```java
System.out.print(age);
```

# 변수의 값 변경
```java
int age = 14;
age = age + 1; #14 + 1 = 15
```

# 두 변수의 값 교환
자바는 변수의 값을 서로 교환하기 위해 추가적인 변수 1개가 더 필요하다.
```java
int a = 20, b = 10;
int tmp;

System.out.println("값 교환 전.");
System.out.println("a = " + a);
System.out.println("b = " + b + "\n");

tmp = a;
a = b;
b = tmp;

System.out.println("값 교환 후.");
System.out.println("a = " + a);
System.out.println("b = " + b);
```

> [출력]
>
> 값 교환 전.<br>
> a = 20<br>
> b = 10
> 
> 값 교환 후.<br>
> a = 10<br>
> b = 20

> [예제2-1](codes/ch2/_1/_1_VarEx.java)<br>
> [예제2-2](codes/ch2/_1/_2_VarEx2.java)
---

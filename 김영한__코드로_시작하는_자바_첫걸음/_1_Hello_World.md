## 인텔리제이 설치
```zsh
brew install --cask intellij-idea-ce
```

JDK는 인텔리제이에서 설치하므로 따로 설치는 안함.

---

## 인텔리제이 실행
1. New Project
2. 다음과 같이 작성
```
Name: java-start
Location: documents/Java_codes
Create Git repository 선택하지 않음
Language: Java
Build system: IntelliJ
JDK: Oracle OpenJDK 21 
`Add sample code` 선택
```
3. create 클릭
4. 만약 한글이라면 영어로 변경
```
IntelliJ IDEA(메뉴) Settings... Plugins Installed
```

---

## 자바 프로그램 실행
### HelloJava
#### 코드
```java
public class HelloJava {
  public static void main(String[] args) {
    System.out.println("hello java");
  }
}
```
#### 실행 결과
```zsh
hello java
```

#### 설명
* 파일명과 클래스 이름이 같아야함
* main(String[] args)는 메서드라고 한다(메서드 개념은 뒤에 나옴), 메서드를 찾아서 프로그램을 시작한다.

### HelloJava2
#### 코드
```java
public class HelloJava2 {
  public static void main(String[] args) {
    System.out.println("hello java1");
    System.out.println("hello java2");
    System.out.println("hello java3");
  }
}
```

#### 실행 결과
```zsh
hello java1
hello java2
hello java3
```

---

## 주석(comment)
### 주석의 종류
* 한줄 주석 -> //
* 여러줄 주석 -> /* */

### CommentJava
#### 코드
```java
public class CommentJava {
    public static void main(String[] args) {
        System.out.println("hello java1"); //hello java1을 출력합니다.
        //System.out.println("hello java2");

        /*
        System.out.println("hello java3");
        System.out.println("hello java4");
        */
    }
}
```

#### 실행 결과
```zsh
hello java1
```

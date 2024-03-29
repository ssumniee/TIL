# 변수

### Intro

> 프로그래밍은 데이터를 처리하는 과정이다.  
> 변수 사용은 데이터를 편리하게 저장하고 꺼내 쓰는 것이다.

#

### 변수의 선언과 값의 할당

#### 메모리

> 컴퓨터에는 데이터를 위한 보관함인 메모리가 존재한다.  
> 이 보관함의 크기는 모두 동일하다.

#### 변수

> 각 보관함의 이름이자 데이터의 이름표이다.  
> 이 변수를 통해 보관된 데이터를 사용할 수 있다.

#### 선언 Declaration

- 데이터를 보관할 메모리를 확보하는 것이 변수의 선언이다. 선언 키워드를 통해 이루어진다.

  ```js
  let foo;
  ```

#### 할당 Assignment

- 보관함에 데이터를 저장하는 것이 값의 할당이다. 등호(=)를 통해 이루어지며, 이는 같다는 뜻이 아닌 우측 값을 좌측 변수에 저장한다는 의미이다.

  ```js
  foo = "hello!";
  ```

#### 선언 + 할당

- 선언과 할당을 동시에 할 수도 있다.

  ```js
  let var = "hi!";
  ```

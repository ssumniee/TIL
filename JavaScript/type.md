### Intro

> 변수에는 다양한 타입이 있다.
> 타입마다 각기 다른 속성(property)과 메소드(method)를 갖는다.

> **원시 자료형**
> 고정된 저장 공간(메모리)을 차지하는 자료형이다.
> 원시 자료형은 모두 하나의 데이터를 값으로 갖는다.
> e.g. `string`, `number`, `boolean`, `undefined`

> **참조 자료형**
> 자바스크립트에서 원시 자료형이 아닌 모든 변수는 참조 자료형이다.
> 원시 자료형은 하나의 데이터만을 담지만, 참조 자료형은 여러 데이터를 담을 수 있다.
> e.g. `array`, `object`, `function`

- **String**
  문자열을 나타내는 변수 타입이다.

      ```jsx
      let name = "leezy"; // string
      ```

- **Number**
  숫자를 나타내는 변수 타입이다.

      ```jsx
      let age = 100; // number
      ```

- **Boolean**
  참/거짓을 나타내는 변수 타입이다.

      ```jsx
      let isAdult = true; // boolean
      ```

- **Undefined**
  값이 할당되지 않음을 나타내는 변수 타입이다.

      ```jsx
      let foo; // undefined
      ```

### 특정 값의 타입 확인

> **typeof**
> 피연산자 앞에 위치하며, 피연산자의 자료형을 문자열로 반환한다.
> 자료형을 가져올 객체 또는 원시값을 나타내는 표현식을 매개변수로 한다.

- **typeof 연산자**
  `typeof`를 활용하여 특정 값의 타입을 확인할 수 있다.

      ```jsx
      let age = 27;
      console.log(typeof age); // expected output: "number"

      let myname = 'leezy';
      console.log(typeof myname); // expected output: "string"

      let isAdult = true;
      console.log(typeof isAdult); // expected output: "boolean"
      ```

### 비교 연산자

> **엄격한 비교**
> 변수의 값 뿐만 아니라 타입까지 고려한 비교를 의미한다.

- `**==` `!=` : 일반적 비교\*\*
  변수 타입은 비교하지 않으므로 사용을 지양해야 한다.

      ```jsx
      1 == "1" // 숫자 1과 문자열 "1"은 같다
      ```

- `**===` `!==` : 엄격한 비교\*\*
  변수 타입까지 고려해서 비교한다.

      ```jsx
      1 !== "1" // 숫자 1과 문자열 "1"은 (엄격하게) 같지 않다
      ```

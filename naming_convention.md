# 명명법

## 용어
  * 약자 및 용어 맨 처음 등장 시, 영어 원문 그대로
    사용
    ex. 백트래킹(Back Tracking) 이후, 한글 사용

  * 지정 교재에서 확인한 단어 사용

## 코드
  * 주석 : #으로 통일

  * 변수, 함수, 파일명 : `snake_case`
  * 클래스 : `CamelCase`
  * 의미 없는 변수 : a, b, c 사용 x (반복문 내 i, j, k는 허용)


## 함수명 (Function Name)

- 소문자와 밑줄(snake_case) 사용
- 동작을 설명하는 동사 또는 동사구 사용


  ```python
    def calculate_total():
    ...

    def send_email_notification():
    ...
  ```

## 클래스명 (Class Name)

  - CamelCase (PascalCase) 사용

  - 명사 또는 명사구 사용
    ```python
    class ShoppingCart:
        ...

    class HttpRequest:
        ...
    ```

## 변수명
- 지역 변수 및 인스턴스 변수: snake_case

- 상수는 UPPER_SNAKE_CASE
- 단, 반복문 등에서는 i, j, k와 같은 짧은 이름 허용
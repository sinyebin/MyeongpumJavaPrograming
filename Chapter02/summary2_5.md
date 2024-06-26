## 2.5 연산

### 식과 연산자

**연산**: 주어진 식을 계산하여 결과를 얻어내는 과정

### 연산자 우선순위

여러 개의 연산자가 있는 경우, 우선순위가 높은 연산자를 먼저 처리

### 산술 연산

**산술 연산자**: 더하기(+), 빼기(-), 곱하기(*), 나누기(/), 나머지(%)

%연산자는 홀수, 짝수 구분할 때 유용하게 활용

    int r=n%2; //n이 홀수면 r은 1, 짝수이면 r은 0

n값이 3의 배수인지 확인하기 위해서도 활용

    int s=n%3; //n이 3의 배수이면 s는 0

### 증감 연산

**증감 연산자** ++,-- 두가지

    int a=1;
    a++; //a값 1 증가. a는 2
    ++a; //다시 a 값 1증가. a는 3

전위 연산자: 연산자가 변수의 앞에 붙을 때

    a=1;
    b=++a; //a=2, b=2

후위 연산자: 연산자가 변수의 뒤에 붙을 때

    a=1;
    b=a++; //a=2, b=1

### 대입 연산

**대입 연산자**: 연산자의 오른쪽 식의 결과를 왼쪽에 있는 변수에 대입

    int a=1, b=3;
    a=b; //b값을 a에 대입하여 a=3
    a+=b; // a=a+b의 연산이 이루어져, a=6, b=3

### 비교 연산과 논리 연산

**비교 연산자**: 두 개의 피연산자를 비교하여 true, false의 논리값을 내는 연산자
논리 연산자: 논리 값을 대상으로 AND, OR, XOR, NOT의 논리 연산을 하여 논리 값을 내는 연산자

    (age>=20)&&(age<30) //나이 (int age)가 20대인 경우
    (c>='A')&&(c<='Z') //문자 (char c) 가 대문자인 경우
    (x>=0) &&(y>=0)&&(x<=50)&&(y<=50) (x,y)가 (0,0)과 (50,50)의 사각형 내에 있음

### 조건 연산

**조건(삼항) 연산자**: 조건문이 true일 경우 결과 값은 opr2, false일 경우 opr3

    condition? opr2: opr3


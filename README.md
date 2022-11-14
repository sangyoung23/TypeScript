# TypeScript

# 타입 추론

// a에 선언된 값이 숫자 5이기 때문에 a에 타입은 자동으로 숫자타입으로 정해졌기 때문에 a에 "hello"를 재할당 할려고 하면 에러가 난다.
let a = 5
a = "hello"
// 타입스크립트는 타입 표기가 없는 경우 코드를 읽고 분석하여 타입을 유추해낼수 있다. 이러한 것을 타입 추론이라고 한다.


// 뺄셈 연산자를 보고 타입 추론에 의하여 lostPoint가 number이라고 정의 한다.
function calculateCoding (lostPoint) {
    return 100 - lostPoint;
}

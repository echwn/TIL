# 3/21(수)

## 1. Today I learned

### 1-1. git에서 관리하는 세 영역

- 작업 디렉토리 (Working directory)
  - 현재 편집 중인 파일이 저장되는 영역
- 스테이징 영역 (Staging area)
  - 저장소에 저장할 변경 사항을 보관하는 임시 저장소
- .git 디렉터리 (Repository)
  - 모든 작업 내역이 영구히 저장되는 저장소

### 1-2. JavaScript 표현식(expression)과 연산자(operator)

```// 논리 연산
true || false;
true && false;

// 진리값으로 취급하기
1 || 0;
1 && 0;
```

## 2. Today I found out

애니악 이전의 기계식 컴퓨터의 동작원리가 인상깊었다. 

## 3. 오늘 읽은 자료
[Github 프로젝트 관리하기](https://git-scm.com/book/ko/v2/GitHub-GitHub-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EA%B4%80%EB%A6%AC%ED%95%98%EA%B8%B0): commit, push, pull

# 3/21(수)

## 1. Today I learned

### 1-1. JavaScript 제어 흐름

초기값이 실행된 후 조건이 true인 동안 반복 갱신

```// for 구문
for (let i = 0; i < 5; i++) { // (초기값; 조건; 갱신)
  console.log(`이 코드는 ${i + 1}번 째 실행되고 있습니다.`);
}
```

괄호 안의 값이 true인지만 체크

```// while 구문
let i = 0;
while (i < 5) {
  console.log('이 코드는 괄호 안의 값이 `true`인 한 계속 실행됩니다.')
  i++;
}
```



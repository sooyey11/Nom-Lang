# 놈랭 (Nom-Lang)
Noman Idiot Programming Language (노우맨 멍청이 프로그래밍 언어)

놈랭은 [엄랭](https://github.com/rycont/umjunsik-lang) 언어에서 파생된 난해한 프로그래밍 언어 입니다. 노우맨이 누구냐고요? 제 친구 닉네임 인데요 ㅋㅋ

```
놈우?
놈놈우?

우노!
우노노!

놈노-
놈놈노노-

놈놈놈+++
놈놈놈놈맨노노노ㅋ

안해노노
```

**출처** : [rycont/umjunsik-lang](https://github.com/rycont/umjunsik-lang)

# 문법
놈랭은 "노", "우", "맨", "멍청아", "안해" 5개의 키워드와 "+", "-", "!", "?", "ㅋ", "ㅎ" 6개의 기호로 이루어 집니다.

## 자료형
정수는 "+"로, 실수는 "-"로 표현합니다.

```
+++ => 3
- => -1
+++++ => 5
-- => -2
+-- => -1
-+ => 0
```
## 변수
변수는 변수명을 지정하는것이 아닌 n번째 변수를 통해 만들고 대입할수 있습니다. 대입값이 없으면 기본값은 0으로 설정합니다.

키워드 뒤에 붙은 자료형을 통해 저장합니다.

### 대입
대입은 **"놈"** 키워드로 합니다. **"놈"** 의 글자수에 따라 몇번째 변수인지 알수 있습니다.
```
놈 => 1번째 변수에 0 저장
놈놈+++ => 2번째 변수에 2 저장
놈놈놈+ => 3번째 변수에 1 저장
```

#### 문자와 문자열 대입
문자를 변수에 대입하고 싶으면 **"놈ㅎ"** 키워드로 합니다. "놈" 과 "ㅎ" 사이에 문자를 집어 넣으면 됩니다.
```
놈aㅎ => 1번째 변수에 a 저장
놈놈Qㅎ => 2번째 변수에 Q 저장
놈놈놈lㅎ => 3번째 변수에 l 저장
```

문자열을 변수에 대입하고 싶으면 **"놈ㅋ"** 키워드로 합니다. "놈" 과 "ㅋ" 사이에 문자열을 집어 넣으면 됩니다.
```
놈Hiㅋ => 1번째 변수에 Hi 저장
놈놈Hello, world!ㅋ => 2번째 변수에 Hello, world! 저장
놈놈놈Josbarㅋ => 3번째 변수에 Josbar 저장
```

### 제거
변수 제거는 **"말살하라"** 키워드로 합니다. **"말살하라"** 키워드 뒤에 붙는 **"!"**(느낌표) 의 갯수번째 변수를 제거합니다.
```
말살하라! => 첫번째 변수 제거
말살하라!!!! => 네번째 변수 제거
말살하라!! => 두번째 변수 제거
```

### 사용
사용은 **"노"** 키워드로 합니다. **"놈"** 의 글자수에 따라 몇번째 변수인지 알수 있습니다.
```
노 => 1번째 변수 사용
노노 => 2번째 변수 사용
노노노 => 3번째 변수 사용
```

## 콘솔
### 우!
정수를 출력합니다.
```
우++! => 콘솔에 2 출력
우노노! => 콘솔에 2번째 변수 출력
```

### 우ㅋ
문자열을 출력합니다.
```
우Hiㅋ => 콘솔에 Hi 출력
우Hello, World!ㅋ 콘솔에 Hello, World! 출력
```

### 우?
정수를 입력받습니다. 입력 받기 전 메세지도 출력할수 있습니다.
```
우Name: ? => 콘솔에 Name: 출력 후 정수 입력 받기
우? => 콘솔에 정수 입력 받기
```

## 카운트
### 맨ㅋ
**"맨ㅋ"** 키워드 안에 있는 변수나 문자열들의 길이를 카운트 해줍니다.
```
맨asdfㅋ => 4 반환
맨노노ㅋ => 2 번째 변수의 길이 반환
```

## 지시문
### 안해
**"안해"** 뒤에 오는 값을 반환하고 종료 합니다.
```
안해+++ => 3 반환 후 종료
안해-- => -2 반환 후 종료
안해노노노 => 3 번째 변수의 값 반환 후 종료
```

## 기타
- 확장자는 `.nom` 입니다.
- 놈랭은 인터프리터 언어 입니다.

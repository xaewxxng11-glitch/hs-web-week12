# 12주차 · HTML5 DOM 활용

DOM 구조 이해 및 요소 제어

- 과목: 한신대학교 웹프로그래밍 (AS006-E)
- 주차 강의안: https://hs-web.dreamitbiz.com/weeks/12

## 여는 방법

1. 압축을 풉니다.
2. VS Code 에서 **폴더째로** 엽니다 (파일 → 폴더 열기).
3. `.html` 파일을 더블클릭하면 브라우저에서 바로 열립니다.
   VS Code 라면 Live Server 확장을 쓰는 편이 편합니다 — 저장하면 화면이 바로 바뀝니다.
4. 고쳐 보고, 저장하고, 브라우저를 새로고침(F5)하세요.

**고쳐 보라고 드리는 파일입니다.** 망가뜨려도 괜찮습니다 — 다시 받으면 됩니다.

## 학습 목표

- DOM이 무엇인지 설명하고 HTML 문서와의 관계를 말할 수 있다.
- querySelector로 요소를 찾고 내용·속성·클래스를 바꿀 수 있다.
- textContent와 innerHTML의 차이와 보안 위험을 설명할 수 있다.
- 요소를 만들어 붙이고 지울 수 있다.
- querySelector가 null을 돌려주는 원인을 진단할 수 있다.

## 이번 주 낱말

DOM · querySelector · textContent · innerHTML · XSS · classList · dataset · createElement

## 담긴 파일

### examples/ — 강의안에 나온 예제 8개

- `examples/01.html` — querySelector — CSS 선택자를 그대로 씁니다
- `examples/02.html` — ① 선택자 오타 ② script가 너무 일찍 실행됨
- `examples/03.html` — querySelectorAll은 배열이 아닙니다
- `examples/04.html` — 글자 바꾸기
- `examples/05.html` — 입력과 값
- `examples/06.html` — 스타일 — 클래스로 바꿉니다
- `examples/07.html` — 속성 다루기
- `examples/08.html` — createElement + append

### lab/ — 실습 3개

- `lab/lab1.html` — 실습 1 · 기본
- `lab/lab2.html` — 실습 2 · 기본
- `lab/lab3.html` — 실습 3 · 응용

문제와 힌트는 각 실습 파일 맨 위 주석에 그대로 적어 두었습니다.
모범답안은 `lab/answer/` 에 있습니다. **먼저 스스로 해 본 뒤에** 열어 보세요.

## 다 만들었으면

실습 결과를 패들릿에 올려 자랑해 주세요.
주차 강의안 페이지 **맨 위**의 [12주차 실습 자랑하기] 단추로 들어갑니다.

> 패들릿은 **서로 보고 배우는 자랑·질문용**입니다. 성적과는 관계가 없습니다.
> 성적에 들어가는 **실습 과제는 학교 LMS에 제출**합니다 — https://lms.hs.ac.kr/

- 실습 결과(화면 캡처) → 「12주차 실습 제출」 칸
- 막히거나 안 되는 것 → 「12주차 질문·막힌 곳」 칸

https://padlet.com/dreamitbiz/hs2605

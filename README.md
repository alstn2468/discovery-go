디스커버리 Go 언어
======================================================
저자 염재현
---------------------------------

### ### CHAPTER 1 시작하기
------------------
```
1.1 Go 언어 소개
· 1.2 첫 프로그램
· 1.2.1 Go 놀이터
· 1.2.2 기본 예제 코드
1.3 자료형 및 변수
· 1.3.1 변수 선언
· 1.3.2 자료형 추론
1.4 함수와 간단한 제어 구조
1.5 마치며
1.6 연습 문제
```

### CHAPTER 2 환경 설정하기
----------------------
```
2.1 설치하기
· 2.1.1 압축 파일로 설치하기
· 2.1.2 소스를 컴파일하여 설치하기
· 2.1.3 PATH에 go 실행 파일 경로 추가하기
· 2.1.4 GOROOT 설정하기
· 2.1.5 Chocolatey로 윈도우 개발환경 간편 설치하기
2.2 작업 공간 설정하기
· 2.2.1 Git 설치하기
· 2.2.2 작업 디렉터리 (GOPATH) 작성하기
· 2.2.3 작업 공간 내의 실행 파일들에 PATH 설정하기
· 2.2.4 내 컴퓨터에서 코드 작성해보기
· 2.2.5 패키지와 라이브러리
2.3 편집기 설정하기
· 2.3.1 LiteIDE
· 2.3.2 Emacs
· 2.3.3 Vim
· 2.3.4 Atom
· 2.3.5 Wide
2.4 도구 사용하기
· 2.4.1 godoc
· 2.4.2 Oracle
· 2.4.3 Vet
· 2.4.4 Fix
· 2.4.5 Test
2.5 마치며
```

### CHAPTER 3 환경 설정하기
------------------
```
3.1 문자열
· 3.1.1 유니코드 처리
· 3.1.2 Example 테스트
· 3.1.3 바이트 단위 처리
· 3.1.4 패키지 문서
· 3.1.5 문자열 잇기
· 3.1.6 문자열을 숫자로
3.2 배열과 슬라이스
· 3.2.1 배열
· 3.2.2 슬라이스
· 3.2.3 슬라이스 덧붙이기
· 3.2.4 슬라이스 용량
· 3.2.5 슬라이스의 내부 구현
· 3.2.6 슬라이스 복사
· 3.2.7 슬라이스 삽입 및 삭제
· 3.2.8 스택
3.3 맵
· 3.3.1 맵 사용하기
· 3.3.2 집합
· 3.3.3 맵의 한계
3.4 입출력
· 3.4.1 io.Reader와 io.Writer
· 3.4.2 파일 읽기
· 3.4.3 파일 쓰기
· 3.4.4 텍스트 리스트 읽고 쓰기
· 3.4.5 그래프의 인접 리스트 읽고 쓰기
3.5 마치며
3.6 연습문제
```

### CHAPTER 4 함수
--------------
```
4.1 값 넘겨주고 넘겨받기
· 4.1.1 값 넘겨주기
· 4.1.2 둘 이상의 반환값
· 4.1.3 에러값 주고받기
· 4.1.4 이름 있는 결과 인자(Named return parameter)
· 4.1.5 가변인자
4.2 값으로 취급되는 함수
· 4.2.1 함수 리터럴(Function literal)
· 4.2.2 고계 함수(High-order function)
· 4.2.3 클로저(Closure)
· 4.2.4 생성기
· 4.2.5 이름 있는 자료형
· 4.2.6 이름 있는 함수형
· 4.2.7 인자 고정
· 4.2.8 패턴의 추상화
· 4.2.9 자료구조에 담은 함수
4.3 메서드
· 4.3.1 단순 자료형 메서드
· 4.3.2 문자열 다중 집합
· 4.3.3 포인터 리시버
· 4.3.4 공개 및 비공개
4.4 활용
· 4.4.1 타이머 활용하기
· 4.4.2 path/filepath 패키지
4.5 마치며
4.6 연습문제
```

### CHAPTER 5 구조체 및 인터페이스
----------------------------
```
5.1 구조체
· 5.1.1 구조체 사용법
· 5.1.2 const와 iota
· 5.1.3 테이블 기반 테스트
· 5.1.4 구조체 내장
5.2 직렬화와 역직렬화
· 5.2.1 JSON
· 5.2.2 Gob
5.3 인터페이스
· 5.3.1 인터페이스의 정의
· 5.3.2 커스텀 프린터
· 5.3.3 정렬과 힙
· 5.3.4 외부 의존성 줄이기
· 5.3.5 빈 인터페이스와 형 단언
· 5.3.6 인터페이스 변환 스위치
5.4 마치며
5.5 연습문제
```

### CHAPTER 6 웹 애플리케이션 작성하기
-------------------------
```
6.1 Hello, 세계!
6.2 할 일 목록 관리 웹 앱 만들기
· 6.2.1 RESTful API
· 6.2.2 Data Access Object
· 6.2.3 RESTful API 핸들러 구현
· 6.2.4 RESTful 서버 완성
· 6.2.5 HTML 템플릿 작성하기
6.3 코드 리팩토링
· 6.3.1 통일성 있게 파일 나누기
· 6.3.2 라우터 사용하기
6.4 추가 주제
· 6.4.1 HTTP 파일 서버
· 6.4.2 몽고디비와 연동하기
6.5 마치며
6.6 연습문제
```

### CHAPTER 7 동시성
--------------------
```
7.1 고루틴
· 7.1.1 병렬성과 병행성
· 7.1.2 고루틴 기다리기
7.2 채널
· 7.2.1 일대일 단방향 채널 소통
· 7.2.2 생성기 패턴
· 7.2.3 버퍼 있는 채널
· 7.2.4 닫힌 채널
7.3 동시성 패턴
· 7.3.1 파이프라인 패턴
· 7.3.2 채널 공유로 팬아웃하기
· 7.3.3 팬인하기
· 7.3.4 분산처리
· 7.3.5 select
· 7.3.6 파이프라인 중단하기
· 7.3.7 컨텍스트(context.Context) 활용하기
· 7.3.8 요청과 응답 짝 짓기
· 7.3.9 동적으로 고루틴 이어붙이기
· 7.3.10 주의점
7.4 경쟁 상태
· 7.4.1 동시성 디버그
· 7.4.2 atomic과 sync.WaitGroup
7.5 문맥 전환
7.6 마치며
7.7 연습문제
```

### CHAPTER 8 실무 패턴
-------------------
```
8.1 오버로딩
· 8.1.1 연산자 오버로딩
8.2 템플릿 및 제너릭 프로그래밍
· 8.2.1 유닛 테스트
· 8.2.2 컨테이너 알고리즘
· 8.2.3 자료형 메타 데이터
· 8.2.4 go generate
8.3 객체지향
· 8.3.1 다형성
· 8.3.2 인터페이스
· 8.3.3 상속
· 8.3.4 캡슐화
8.4 디자인 패턴
· 8.4.1 반복자 패턴
· 8.4.2 추상 팩토리 패턴
· 8.4.3 비지터 패턴
8.5 마치며
```

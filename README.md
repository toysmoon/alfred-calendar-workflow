# 설치

## Workflow File 실행

```
korean-calendar.alfredworkflow
```

## 기본 프로젝트 이름 설정

Alfred Preferences -> Workflows -> Apple Calendar -> open (Run Script)

프로젝트 이름을 아래 부분을 찾아서 수정해주세요.

```
const projectName = '개인'
```

# 사용

## Keyword

- cal
- 오늘 (이벤트 시작 시간이 오늘이 됩니다.)
- 내일 (이벤트 시작 시간이 내일이 됩니다.)

## 인식 가능한 단어

- 오늘
- 내일
- 12/23
- 3시
- 15-17시

## 참고사항

- 애플 기본 캘린더에만 적용됩니다.
- 기본적으로 인식 가능한 단어는 공백으로 구분해야 합니다.
- 이벤트는 기본적으로 종일로 설정되어 있습니다.
- 시간단위로만 설정 가능합니다.
- 시간을 하나만 입력하면 1시간이 기본입니다.
- 날짜를 여러번 입력하면 범위로 지정됩니다.

## 예제

```
cal 내일 15시 프로젝트 마감
cal 03/01 3/2 부산 여행
오늘 21-23시 영화 관람
내일 20시 과자사기
```
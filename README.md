# TDD를 적용해서 todo planner 만들기

## 만들고 싶은 앱

단계별로 중요도에 따라 하루 계획을 세울 수 있는 앱

## 관련 정보

* 배포 사이트 링크 : [TDD-todo-planner]()

* 작업 기간 : 230607 ~ (230707 한달 목표)

* 프로젝트 의의 : TDD를 연습하고, 익힌다.

## Preview

![배포 사이트 미리보기]()

## 기능 구현 목록 및 테스트 명세 항목

### ver 1.0.0

**todo를 입력하고, 카테고리에 맞춰 todo를 이동시킨다**

-[ ] input에 오늘 할 일을 입력한 뒤 버튼을 클릭하면 'unclassified' div에 업로드된다.

-[ ] unclassified에 있는 todo를 drag & drop을 이용해 personal 또는 work div에 옮긴다.

-[ ] todo 우측에 있는 button 중 별 button을 누르면 각 div의 최상단으로 올라간다. (section div 내부에 중요 일정용 div가 생긴다.)

-[ ] todo 우측에 있는 button 중 삭제 button을 누르면 div에서 삭제된다.

-[ ] todo 왼쪽에 있는 button을 누르면 todo content에 가운데 줄이 생긴다.

### ver 2.0.0

**todo를 완료하면 시작 시각과 종료 시각의 범위만큼 time table 내 공간에 배경색을 갖는다**

-[ ] todo 왼쪽에 있는 버튼을 누르면 todo content 바로 밑에 시작 시각과 종료 시각을 입력하는 input이 생긴다.

-[ ] 시작 시각과 완료 시각을 입력하면 time table에 해당 시간부분이 색칠되고, todo의 별 버튼이 비활성화된다.

-[ ] 시작 시각과 완료 시각 우측에 있는 X 버튼을 누르면 input이 없어지고, todo의 별 버튼이 비활성화된다.

## TIL (프로젝트 기록)

* [230607_멘토님과 함께한 모각일 시간](TIL/230607.md)
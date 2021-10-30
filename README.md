# 49EHyeon42 Git 명명 규칙


## 저장소
```
[필수: 이름]-[필수: 목적]-[선택 사항: 플랫폼, OS]-[필수: 언어]
```

| 구성 | 설명 |
|:---: | :---: |
| 이름 | 저장소를 나타내는 이름 |
| 목적 | 저장소의 목적 또는 역할 |
| 언어 | 저장소가 동작하는 언어 |

1. 저장소를 명명할 때 **[필수: 이름]-[필수: 목적]-[선택 사항: 플랫폼, OS]-[필수: 언어]** 구조를 따른다.
2. 저장소 명명시 **소문자**, **붙임표(-)** 를 사용한다.
5. 플랫폼을 통해 언어가 유추될 경우 플랫폼을 사용한다.
6. 특정 환경에서 동작하는 경우 OS를 작성한다.

## README.md

참고 : https://github.com/matiassingers/awesome-readme
참고 : https://github.com/jehna/readme-best-practices#readme
참고 : https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/

## commit
타입 제목 <type>[optional scope]: <description>

본문 [optional body]

꼬리말 [optional footer(s)]

 제목(Title)
 - 타입(Type)
  - 제목(Subject)
  본문(Body)
  꼬리말(
  
  
  
### 타입
Feat - 새로운 기능을 추가할 경우, 새로운 기능 추가 - a new feature
Fix - 버그를 고친 경우, 버그 수정 - a bug fix
Design - CSS등 사용자 UI 디자인 변경
!BREAKING CHANGE - 커다란 API 변경의 경우
!HOTFIX - 급하게 치명적인 버그를 고쳐야하는 경우
Style - 코드 포맷 병경, 세미 콜론 누락, 코드 수정이 필요 없는 경우, 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 - formatting, missing semi colons, etc;no code change
Refactor - 프로젝트 코드 리팩토링, 코드 리펙토링
Comment - 필요한 주석 추가 및 변경
Docs - 문서를 수정한 경우(코드 제외), 문서 수정 - changes to documentation
Test - 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X), 테스트 코드, 리펙토링 테스트 코드 추가 - adding tests, refactoring test; no production code change
Chore - 빌드 테스트 업데이트, 패키지 매니저를 설정하는 경우 (프로덕션 코드 변경 X), 빌드 업무 수정, 패키지 매니저 수정 - updating build tasks, package manager configs, etc; no produnction code change
Rename - 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
Remove - 파일을 삭제하는 작압만 수행한 경우

### 타입의 종류
기능 - feat fix desin !BREAKING
개선 - style refacotr comment
그 외 - docs test chore rename remove

### 제목 subject
처음은 동사 원형으로 시작하고 총 글자 수는 50자 이내로 작성한다.
마지막에 특수문자는 삽입하지 않는다.
제목은 개조식 구문으로 작성한다.
과거 시제를 사용하지 않고, 명령어로 작성한다.

만약 영어로 작성하면 첫 글자는 대문자로 태그의 명령어로 시작한다
한글은 고침 추가 변경의 명령어로 시작한다.

### 본문 body
본문은 한 줄 당 72자 내로 작성한다.
본문 내용은 양에 구애받지 않고 최대한 상세히 적성한다.
본문 내용은 어떻게 변경했는지 보다 무엇을 변경했는지 또는 왜 변경했는지 설명한다.

### 꼬리표
꼬리말은 optional 이고 이슈 트래커 ID를 작성한다.
꼬리말은 "유형:#이슈 번호" 형식으로 사용한다.
여러개의 이슈 번호를 적을 때는 쉼표로 구분한다.
이슈 트래커 유형은 다음 중 하나를 사용한다. 
- Fixes 이슈 수정 중
- Resolves 이슈를 해결했을 때 사용
- Ref 참고할 이슈가 있을 때 사용
- Related to 해당 커밋에 관련된 이슈 번호
- ex ) Fiex: #45 Related to: #34, #23



## branch
master branch
develop branch
feature branch
release branch
hotfix branch

1. 저장소
2. 리드미
3. 커밋

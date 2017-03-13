# 좋은 커밋 규칙

## 훌륭한 Git 커밋 메시지의 일곱 가지 규칙

1. 제목과 본문을 빈 행으로 분리한다.

2. 제목 행을 50자로 제한한다.
    - GitHub UI는 이런 관례를 잘 알고 있다. 만약 50자 이상을 입력하려고 시도하면 경고 표시가 나타난다.
    - 69자 이상 제목 행이라면 다음처럼 줄임 표시가 나타난다.
    - 50자를 기준으로 적되, 최대 상한선은 69자임을 염두에 두자.

3. 제목 행 첫 글자는 대문자로 쓴다.

4. 제목 행 끝에 마침표를 넣지 않는다.

5. 제목 행에 명령문을 사용한다.(동사의 현재형으로 시작한다.)
    - 네 방을 치운다 (Clean your room)
    - 문을 닫는다 (Close the door)
    - 쓰레기를 갖다 버린다 (Take out the trash)

6. 본문을 72자 단위로 개행한다.
    - vim 에디터에서 72자가 넘으면 자동으로 개행이 되는 관습에서 나오게 되었다.

7. 어떻게 보다는 무엇과 왜를 설명한다.

8. 한글로 쓰는 것이 좋다.


## 커밋 log를 사용하는 이유
- 리뷰 프로세스를 가속 시킨다.
- 릴리즈 노트 작성시 해당 코드에대한 내용을 보는것에 도움이 된다.
- 미래에 유지보수시 도움이 된다. 나중에 코드의 변경 사항을 쉽게 인지 할 수 있다.

## Tip
- https://item4.github.io/2016-11-01/How-to-Write-a-Git-Commit-Message/
- git commit -m ""은 한줄 메세지 작용 시 사용한다. 보통 한줄 이상의 커밋 메시지를 작성한다.


## ETC
- commit log는 각 팀에서 직접 정하고 만드는 것이 좋다.
- major(<>), minor를 나누어 작성할 수 있다. change log를 작성하여 버전의 변경사항을 한눈에 볼 수 있다.
- major와 minor의 내용이 구분 되어야 한다.



## 나만의 commit log 규칙

### 제목

 - 제목의 행은 50자 이내로 작성한다.
 - major 기능의 commit log의 제목은 [] (대괄호)로 감싼후 우선순위를 작성해 준다.
    ex) **[1. log제목]**
 - minor 기능의 commit log의 제목은 () (괄호)로 감싼후 우선순위를 작성해 준다.
    ex) **(1. log제목)**
 - communication을 위해 commit log의 제목은 및 본문은 한글로 작성한다.
 -

### 내용
 - 제목과 내용 사이는 빈 행으로 분리한다.
 - 본문의 내용이 72자 이상 이면 개행 한다.

ex)

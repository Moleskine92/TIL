# 리눅스 기본 명령어

## 0. 명령어의 기본형식
```
command [options] [arguments]
```
대괄호로 묶었다는 건 넣을 수도, 넣지 않을 수도 있다는 말.
전자는 ? 후자는 실제로 활용할 데이터

 - command : 실행할 명령어, 프로그램
 - options : 명령어의 옵션
 - arguments : 명령어에 전달할 인자


 ## 1. 파일 및 디렉토리 관리

 ### ls (list)
  - 디렉토리 내용 목록을 보여줌
  - options:
    - `-1` : 파일의 상세 정보 표시
    - `-a` : 숨김 파일 표시

    명령어 입력 시 나오는 점은 현재, 점점은 상위 폴더
    리눅스에서 .으로 시작하는 폴더는 전부 숨김 처리

    ### cd (chnage directory)
    - 현재 작업 디렉토리를 변경합니다. 클릭 같은 개념.
    쉽게 이동하려면 첫 글자만 쓰고 탭을 누르면 자동완성이 됨
    오타가 날 것을 대비하는 일도 됨. 단어가 겹치는 경우 겹치는 부분까지만 작성되고, 여기서 탭을 두 번 누르면 디렉토리가 두 번 나옴.
    - `cd {target directory}
        - target-directory는 자동완성 기능을 활용 (TAB)

    ### pwd (print working directory)
    - 현재 작업 중인 디렉토리의 전체 경로를 출력.
    
    ### mkdir (make directory)
    - 새로운 디렉토리를 생성.
    - 사용방법 `mkdir {directory-name}`

    ### touch
    - 새로운 파일을 생성.
    - `touch {file-name}
    
    ### rm (remove)
    - 기존 파일을 삭제. 폴더는 못 지움. 하나 지우는 게 기능. 하지만? 방법은 있다.
    - rm {file-name}
    - options (폴더를 지우는 법)
        - `-r`: 디렉토리와 그 내용을 재귀적으로 삭제

    ### cat (concatenate)
    - 파일의 내용을 출력. 파일 저장이 되어있어야 접근 가능.
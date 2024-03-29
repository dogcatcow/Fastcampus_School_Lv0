# 1일차 과제

## [필수] 마크다운 문법이란
- 마크다운(markdown)은 일반 텍스트 문서의 양식을 편집하는 문법. 
- README 파일이나 온라인 문서나 일반 텍스트 에디터로 문서 양식을 편집할 때 사용됨.
- 마크다운을 이용해 작성된 문서는 HTML 등 다른 문서형태로 변환이 가능.

## [필수1] 빈칸 채우기

1. git에서 지금까지의 모든 변경된 작업내역이 영구히 저장되는 곳은 ( 레포지토리   ) 입니다.
    - 왜 이 답을 쓰셨는지 이유를 작성해주세요. 
비주얼코드에서 버전관리를 위해 해당 저장소를 지정해놓음.

2. 지금까지 커밋한 내용을 확인하는 명령어는 (  git log   ) 입니다.
    - 왜 이 답을 쓰셨는지 이유를 작성해주세요. ('log': 기록 조회)

3. github에는 다른 사람의 프로젝트를 통째로 복사하는 기능이 있는 이를 (  풀  ) 라고 합니다.
    - 왜 이 답을 쓰셨는지 이유를 작성해주세요. (풀-내 컴퓨터에 다운받기. 클론-새 컴퓨터에 다운받기) 

## [필수2] 서술형으로 풀기
1. git이란 무엇인가요?  
    - 버전관리용 프로그램

2. 프로그래밍에서 버전관리가 필요한 이유는 무엇인가요? 
    - 협업 시 타인의 수정내역 등 참고 필요.

3. git에는 작업 디텍터리(Working Directory), 임시 구역(Staging area), 저장소(Repository)가 있습니다. 
각각 무엇인지 서술하고, 어떤 CLI 명령어를 통해 코드의 변경사항을 각 영역에 저장할 수 있는지 서술해주세요.

    - 1) 작업디렉터리:  편집하는 곳     
    - 2) 임시구역:  작업내용을 임시저장하는 곳. (스테이징)  git add 파일이름
    - 3) 저장소: 커밋한 내용을 저장하는 곳    git commit -m

4. github이란 무엇인가요?
    - 버전관리와 호스팅 서비스 


## [심화1] 서술형으로 풀기
1. git에는 원격저장소와 로컬저장소가 있는데 이 둘의 차이점은 무엇인가요? 
    - 원격: 서버에 저장(업로드), 로컬: 내 컴퓨터에 저장
    
2. git에서 원격 저장소의 상태를 확인하기위해 사용하는 명령어는 무엇인가요?
    - 커맨드라인에 git remote -v 입력. 
 
```git 
mitch@DESKTOP-JPAC2VB MINGW64 ~/Desktop/web (master)

$ git remote -v
origin  https://github.com/dogcatcow/dogcatcow.github.io.git (fetch)
origin  https://github.com/dogcatcow/dogcatcow.github.io.git (push)
```
 
 
## [심화2] 실습해보기
아래 순서를 기반으로 git에 대해 설명하는 파일을 하나 작성한 뒤 github에 업로드 해보세요.

폴더를 만든 뒤 폴더에 들어가서 .git 디렉토리를 git init 명령어를 통해 설치해줍니다.
txt 파일을 만들어줍니다.
파일을 열고 임의의 제목을 입력한뒤 Staging area에 변경사항을 저장하고, Repository에 변경사항을 저장해줍니다. (git add -> git commit)
본문 내용을 1/3만 입력하고 똑같이 Staging area에 변경사항을 저장한 뒤, Repository에 변경사항을 저장해줍니다. (git add, git commit)
[4번] 작업을 두 번 더 반복해줍니다. 
커밋이 4개가 쌓였을 것입니다! github 저장소를 새로 만든 뒤 해당 저장소를 업로드해 주세요.
업로드된 파일들이 담긴 github (원격) 저장소의 링크를 제출해주세요.


https://github.com/dogcatcow/Fastcampus_School_Lv0/commits/master/random.txt

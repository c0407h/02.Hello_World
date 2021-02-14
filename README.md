# 02.Hello_World

## XCode
### 1. Xcode 실행

- 첫 실행 후 새프로젝트 만들기
<img width="798" alt="1  프로젝트시작" src="https://user-images.githubusercontent.com/67133244/107875900-e4dadb80-6f05-11eb-9ab7-6567008e6646.png">

~~~
1. Create a new Xcdoe Project - 아이폰, 아이패드, 맥 앱을 만들기 위한 새로운 Xcode 프로젝트를 생성할 수 있다. 일반적으로 가장 많이 사용
2. Clone an existing project - SVN이나 git 같은 버전 관리 도구로 연결하여 기존 소스를 가져올 수 있다.
3. Open a project or file - 이미 생성된 프로젝트나 파일을 불러 올 수 있다.
4. Recent Projects - 최근에 사용된 프로젝트를 보여준다. 열고자 하는 프로젝트를 선택해서 불러 올 수 있다.
~~~

### 2. 템플릿 선택하기
- 새 프로젝트를 시작할 때 템플릿을 선택하는 창이 나온다.
- 각 템플릿에는 앱을 개발하는데 필요한 기본 틀이 용도별로 설정되어 있다.
- 개발자는 이 기본 틀에 여러 가지 기능을 추가하여 앱을 만들면 된다.
<img width="713" alt="2  템플릿 선택" src="https://user-images.githubusercontent.com/67133244/107876053-db05a800-6f06-11eb-9eca-02b36a3ad972.png">

~~~
1. App - 뷰를 사용하는 앱을 개발할 때 사용하는 템플릿. 
       - 기본적으로 하나의 뷰가 나타나며 필요에 따라 새로운 뷰를 추가하여 만들 수 있다.
       - 일반적으로 가장 많이 사용하는 템플릿
2. Document App - 데이터를 저장할 수 있는 문서 기반의 앱을 개발할 때 사용하는 템플릿
3. Game - 게임 앱을 개발할 때 사용하는 템플릿.
        - 그래픽 처리를 위한 OpenGL 게임뷰를 생성해줌.
4. Augmented Reality App - 증강현실 앱을 개발할 때 사용하는 템플릿
5. Sticker Pack App - 스티커 팩 앱을 개발할 때 사용하는 템플릿
6. iMessage App - 아이메세지 앱을 개발할 때 사용하는 템플릿
~~~

### 3. 프로젝트 기본 정보 입력하기
- 프로젝트의 이름, 사용하는 언어 지정 등 프로젝트의 기본 정보를 입력
<img width="721" alt="3 프로젝트 정보 등록" src="https://user-images.githubusercontent.com/67133244/107876276-70ee0280-6f08-11eb-9754-b950411cc54a.png">

~~~
1. Product Name - 개발하려고 하는 앱의 이름을 입력
2. Team - 개발자 프로그램에 등록된 ID 또는 팀을 입력.
        - 개발자 인증서가 등록되어 있으면 여기서 선택할 수 있다.
        - 시뮬레이션을 사용할 것이면 입력하지 않아도 된다.
3. Organizaation Identifier - 조직의 식별자를 입력
                            - 일반적으로 개인이나 조직의 도메인 주소(URL)를 역순으로 입력
                            - 조직 식별자는 앱 식별자를 만드는 데 사용되므로 공부하는 동안에는 'com.yourcompany'등의 아무 URL을 입력해도 무관
                            - 앱을 앱스토어에 등록하려면 개인이나 조직이 소유하고 있는 유일한 URL이여야한다.
4. Bundle Identifier - 식별자.
                     - CompanyIdentifier.Product Name 으로 자동생성 된다
                     - 앱 식별자는 앱을 앱스토어에 등록할 때 다른 앱들과 구분하는 용도로 사용하므로 유일한 식별자를 사용하여 앱을 등록해야 한다.
5. Interface - 사용하고자 하는 Interface를 선택한다.
             - 스토리보드(StroyBoard)와 스위프트UI(SwiftUI) 중에 하나를 선택할 수 있다.
6. Life Cycle - Interface에 따른 앱의 라이프 사이클을 선택할 수 있다.
7. Language - 앱 개발에 사용할 언어를 선택
            - 스위프트(Swift)나 오브젝티브-C(Objective - C) 중에 하나를 선택할 수 있다
8. Use Core Data - iOS에서 제공하는 데이터 관리 툴킷의 사용 여부를 선택한다.
9. Include Tests - 앱의 동작 등을 자동으로 테스트 할 때 사용한다.
~~~

### 알아두면 좋아요 - 1
<img width="711" alt="소스컨트롤" src="https://user-images.githubusercontent.com/67133244/107876352-d80bb700-6f08-11eb-94f3-bf6652fda5a4.png">

~~~
작업 폴더를 생성하는 단계에서 소스 컨트롤(Source Control)을 사용할지에 대한 선택항목이 있다.
소스 컨트롤은 깃(Git)이라는 소스 버전 관리 도구를 사용하여 프로젝트를 관리하거나 다른 사람들과 협업하고 싶을 때 사용하는 기능
~~~

### 알아두면 좋아요 - 2
- 기기(Device)와 회전 선택하기
- 프로젝트가 생성되고 처음 나타나는 화면이 프로젝트의 설정화면이다.
- 이 부분은 다소 복잡해보여도 초보 단계일 때는 대부분 설정하지 않고 기본으로 사용해도 된다.
<img width="768" alt="기기회전" src="https://user-images.githubusercontent.com/67133244/107876511-b959f000-6f09-11eb-87b3-90aa6e94bce6.png">

~~~
1. Device - 앱이 지원하는 기기를 선택할 수 있다. 
          - 즉, 아이폰, 아이패드 또는 유니버셜 중에서 선택할 수 있다.
2. Device Orientation - 앱이 지원할 회전 방향을 선택할 수 있다.
                      - 세워진 상태(Portrait), 거꾸로 뒤집어진 상태(Upside Down), 왼쪽으로 회전(Landscape Left), 오른쪽으로 회전(Landscape Right)
~~~

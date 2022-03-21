# GIT 깃헙 레파지토리 만들고 연결시키고 푸시까지
<img src="https://user-images.githubusercontent.com/93961708/158679308-34d4ba7f-63e6-4395-b3a3-ca5df36e3697.png"/>

지금 아래에 보이는 왼쪽:우리가사용할공간
<br/>오른쪽:"레파지토리" 만들공간 즉, 쉽게생각해서 "자료를 올릴 공간을 만든다"라는 정도로 생각하시면되겠습니다.
|사용할 공간|레파지토리 만들기|
|:-:|:-:|
|<img src ="https://user-images.githubusercontent.com/93961708/158676466-fce8c387-cad9-4439-97de-7f0fe8b123fb.png"/>|<img src="https://user-images.githubusercontent.com/93961708/158676514-d6737bb7-acf5-47c6-b59f-e229cbc34370.png"/>
<br/>

# 1단계 레파지토리 생성

<br/>
이제 위에 사진과같이 New를 클릭해보면 아래와 같이 화면이 뜨는데
<br/>Onwer : 사용자 Repository name : 레파지토리 이름 즉, 자료공간의 이름 라고 생각하시면됩니다.
<br/>Onwer은 그대로 두시고 Repository name 만 이름지어서 생성 해주시되,
<br/>여기 보이는 public / private 이두개가있는데 저흰 무조건 "Public"으로 할겁니다.
<br/>"쉽게생각해서 공개한다" 라고생각하시면됩니다.
<br/>그리고 밑에 3가지는 지금당장은 필요없으니 손대지말고 생성 하시면됩니다.
<br/>추가로 "Description" 이라는건 레파지토리의 설명이라고 생각하시면됩니다. 이것도 적어주면좋아요!<br/>
<img src ="https://user-images.githubusercontent.com/93961708/158676407-fa4ac78d-6167-486b-8871-2e2a627f365f.png"/>
<br/>

# 2단계_1 레파지토리랑 연결시키기

<br/>
자 이제 만드시면 이상한 영어들이 막 나올건데 너무 당황하지마시고!
<br/>여기서 중요한건 파란색에있는 주소와 2번째에 있는 git 관련 용어들입니다.
<br/>일단 파란색에있는건 이제 "연결시킬 주소" 라고만 생각하시면됩니다.
<br/>이제 차례대로 git 관련 용어들을 알아볼건데
<br/>git init : git을 생성한다!
<br/>git add readme.md : 내가 올릴 자료
<br/>git commit -m "first commit" : 내가 올릴 자료에대한 내용
<br/>git remote add orgin 주소 : 내가 연결 시킬 주소
<br/>git push origin master : 주소에다가 푸시 한다 라고 지금은 간단하게만 알아주세요.
<br/><img src="https://user-images.githubusercontent.com/93961708/158676352-e8f88986-d7d9-447e-8e01-334f246f1e29.png"/>
<br/>

# 2단계_2 레파지토리랑 연결시키기

<br/>
이제 용어를 알았으니 사용해야겠죠? 이제 어떤 도구로 사용해도좋은데 전 개인적으로 "VSCode"로 하고있습니다.
<br/>사실 "Visual studio"는 관리하기가 힘들어요.. 저도 하다가 못해서 강제로 하고있습니다 ㅠㅠ
<br/>그래서 만약에 Visual studio로하실분은 스스로찾아서 해보셔야할듯합니다.. 아시는분 저한테알려주세요..
<br/>근데 이제 Vscode로 하고싶은분은 https://goddaehee.tistory.com/287 이 주소로 가셔서 깔아주시면 감사하겠습니다.
<br/>이제 다운로드 다하셨으면 중간에 이제 "Gitbush" 라고 해서 내가쓰는도구랑 홈페이지랑 연결시켜주는 것이있습니다.
!!!꼭 필요해요!!! https://goddaehee.tistory.com/216 이 주소로 가셔서 똑같이 하시면됩니다! 자 거의 다왔습니다!
<br/>

# 2단계_3 레파지토리랑 연결시키기

<br/>
이제 Vscode를 키시면 저와 유사할겁니다
<br/><img src="https://user-images.githubusercontent.com/93961708/158676570-9fb48be0-e32f-4fe6-bf4b-009d343a6eee.png"/>
이제 파일을 깃에다가 올릴건데 여기 보이시는 터미널에 새 터미널 클릭
<br/><img src="https://user-images.githubusercontent.com/93961708/158676651-82627468-135d-4c22-b083-9798b18912ab.png"/>
하시면 이런식으로 나오는데 "+" 기호 오른쪽 밑 화살표에 "GitBash"라고있습니다
<br/><img src="https://user-images.githubusercontent.com/93961708/158676758-7628bd7c-b6a9-4bf0-93d9-00a4b92cd9a1.png"/>
밑과 같이
<br/><img src="https://user-images.githubusercontent.com/93961708/158676837-79b5fcd1-dcfb-4b7d-b845-a4b13da4435e.png"/>
<br/>이제 "GitBash" 눌러주시면
<br/><img src="https://user-images.githubusercontent.com/93961708/158676907-34b300e5-e1c0-4a14-b360-455b277d25a6.png"/>


이 사진과 같이 뜨는데 이제부터는 진짜로 중요한게있어요.
<br/>노란색 보시면 막 / 땡땡 / 떙땡 뭐라 적혀있어요.
<br/>겁내지마시고 잘살펴보시면 / 라는건 "어떤 파일 아래라는 뜻"이예요.
<br/>제껄 보면 "/d/Onedrive/바탕화면/깃헙저장소" 라는건
<br/>d드라이브 아래에 onedrive 아래에 바탕화면 아래에 깃헙 저장소가 있다는걸 이해할수있어요.
<br/>그래서 이걸왜 알려드리냐. 이제 우리가 있는 위치를 이동시키면서 해야합니다!
<br/>이제 리눅스를 배우시면 아시겠지만 프로그램상 어디로 움직인다
<br/>즉 내위를 이동해줘! 라는 건 "cd" 라는 명령어고 내가 폴더를 생성해서
<br/>만약에 현 위치가 "내가 만든 폴더 위치이다" 이러면 이제부터 시작입니다.
<br/>노란색 마지막에있는 이름이 내가생성한 폴더 이름이랑 같다면 상관없다는 말입니다! 이건 자세히 다루겠습니다
<br/>

# 3단계 푸시 단계

<br/>
자 아까 2단계_1 에서 배웠던 git 관련 용어들을 사용해서 할겁니다.
<br/>git init 라는 명령어를 쳐주세요.(git 생성입니다.)
<br/>그다음 ls -a (모든 파일 확인 명령어) 를 쳐서
<img src="https://user-images.githubusercontent.com/93961708/158677068-bbcefdf2-9158-4745-ad35-87664dc54d5b.png"/>와 같이 뜨면 git이 잘설치 되었다는걸 볼수있습니다.
<br/>이제 내가 올릴 파일 더해줄겁니다 이제 "git add 파일이름"
<img src="https://user-images.githubusercontent.com/93961708/158677156-61648a66-cdc2-4c24-8fb9-2d122494c43f.png"/>
이런식으로해서 "만약 아무말도안뜨면 성공"입니다.
<br/>그다음 커밋 이라고하는데 제목설정이라고생각하시면됩니다.!!이건 꼭해줘야해요!!
git commit -m "제목" 이런식으로하시면<img src="https://user-images.githubusercontent.com/93961708/158677305-7f5784f0-5241-4b81-8675-04e54ec374ac.png"/>
이렇게 뜨시면 성공입니다.
<br/>이제 내가 아까만든 주소랑 연결해야됩니다. 다시 아까 "레파지토리" 만든 창으로 가보시면
<br/><img src="https://user-images.githubusercontent.com/93961708/158677412-c83eb1d0-3de1-4eef-94d0-a108b5ac5cd6.png"/>
여기있는 글 다 쭉 땡겨서 복사후
<br/><img src="https://user-images.githubusercontent.com/93961708/158677516-69f5bf4f-5843-4b7c-80b4-e48b3ad240ee.png"/>
붙여넣기로해주세요.
<br/>그리고나서 "git remote -v" 쳐서 레파지토리 만든 주소랑 같다면 성공하신겁니다!
<br/>이제 정말로 푸시만하면되겠네요.
<br/>명령어는 "git push origin master" 라고 하시면 푸시가되서 이런식으로 올라가신걸 확인할수있습니다.
<br/><img src="https://user-images.githubusercontent.com/93961708/158677585-4ae3c2e5-fc7e-42f9-94c9-2c8c6babaa31.png"/>
<br/>이제 부터는 연결시키는거 제외 즉, "git remote" 이부분은 빼고 사용하시면됩니다!































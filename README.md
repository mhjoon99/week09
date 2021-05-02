# week09

## 팀 전체 진행상황
    
    개인의 프로젝트를 Github를 통해 공유함.
    프로젝트를 새로 만들어 한 프로젝트 내에 각자 맡은 기능의 branch를 추가하기로 함. git을 활용하여 협업을 이어갈 예정임.
    -> 다음주까지 한 repository로 합치기로 함.

### Feedback

    박승준 - (학교/두정역/터미널)의 버스 정보 담당
              데이터 API를 연동하여 정류소명 입력시 정류장 관련 id, 버스 번호 입력시 버스 id 가져오는 기능을 추가함.
              정류소ID와 노선번호를 기준으로하여 실시간 도착정보인 남은 도착시간, 남은 정류장 수를 알 수 있도록 하는 코드 작성완료함.
              정류장 ID값과 노선번호를 입력할 시 해당하는 실시간 버스 정보가 뜨지 않음. 이 오류를 해결 중에 있음.
              정류장 ID값과 노선번호를 통해 검색하는 것이 비효율적이라는 Feedback을 받음.
              정류장 이름을 검색하면 해당하는 정류장ID값이 연결되어 실시간 버스 정보를 받을 수 있도록 수정하기로 함.
    
    김다혜 - 셔틀 버스 정보 및 택시 모집 게시글 담당
             저번주에 맵 구현시 Google API에서 KAKAO API로 변경함. 
             build.gradle에 해당하는 library를 추가하는 코드를 작성했으나, 추가되지 않음.
             회의시간에 Sync Now를 클릭해야 한다는 Feedback을 받고 이 부분에 대해 수정하여 기능을 구현해 오기로 함.
    
    마혜준 - 회원가입/ 로그인 담당
             회원가입을 할 때 사용자가 재학증명서 혹은 입학증명서 이미지 파일을 업로드하고, 이를 관리자가 승인해야 해당 어플의 기능을 사용할 수 있게 하는 부분을 구현 중에 있음.
             이미지를 업로드할 때 카메라를 사용할 지, 갤러리를 사용할지 구현하는 library를 build.gradle에 추가하는 코드를 작성했으나, 추가되지 않음.
             따라서, 갤러리에서 파일을 불러오도록 코드를 수정함.
             이 부분에 대해서 회의 시간에 Sync Now를 추가해야 해당하는 기능이 구현된다고 Feedback을 받음. 다시 이부분에 대해 코드를 수정하기로 함. 또한, 관리자가 실시간으로 확인할 수 있도록 FireBase에 연동하기로 함.
             기존 DB를 수정하여 관리자가 승인을 해야만 회원가입이 0값에서 1값으로 변경되어 회원가입이 완료되도록 하게 구현하자고 feedback을 받음.
    
    박윤빈 - 시간표 담당
             Fragment를 사용하여 레이아웃을 설계하였는데, 이 과정에서 버튼을 누르면 다른 레이아웃으로 이동하는 부분이 오류가 남.
             그 이유는 Fragment 안에 Onclick 함수를 정의할 수 없기 때문인데 OnClick 함수를 Override해서 정의하여 오류를 해결했는데, 다시 오류가 남.
             이 오류에 대해서 계속 해결중.
             우리 어플의 가장 핵심 부분이자, 인터넷에 어떠한 소스도 없는 부분이라 가장 어려운 부분임.
    
    심우정 - 게시판/ 댓글 담당
             게시글을 작성한 시간과 현재 시간을 비교해 글이 작성된 지 얼마나 됐는지 나타내는 기능을 구현하려고 함.
             이 기능을 구현하려고 하는 과정에서 파이어베이스에서 작성된 게시글DB를 불러오는 기능에 오류가 나, 오류를 해결하는 과정에 시간을 뺏김.
             오류를 해결한 후 System.currentTimeMillis()과 SimpleDataFormat을 이용해 글을 작성한 시간을 파이어베이스에 저장하고 게시글 목록에서 작성된 시간을 불러오기까지 진행함.
             현재 시간과 비교하는 걸 더 시도한 후에 댓글 기능을 구현할 예정
    
    양하은 - 메인화면/ 채팅/ 졸업학점 담당
             메인화면에 학교 홈페이지와 연동되는 icon(학교 홈페이지/교내 공지사항/학교 e-campus)을 추가하여 어플을 통해 홈페이지로 바로 들어갈 수 있도록 함.
             어플 하단에 홈/게시판/시간표/교통 Fragment를 추가하여 각각의 icon을 클릭하면 해당하는 layout으로 이동하게 구현함.
             좌측 메뉴를 클릭하여 layout 변경시, 하단 layout 변경 fragment가 사라지는 오류가 발생함. 이 오류를 해결중.
             채팅방에 사람을 초대하는 기능 구현중.
            

## 개인 GitHub URL
    박승준 - https://github.com/parkseungjun12/TeamProject.git
    
    김다혜 - https://github.com/dahye828/SMUtime
    
    마혜준 - https://github.com/mhjoon99/Smutime_login
    
    박윤빈 - https://github.com/yunbin-park/TeamProj_TimeTable
    
    심우정 - https://github.com/ShimWooJeong/SMP_Board
    
    양하은 - https://github.com/Yanghaeun716/FirebaseListexample,
            https://github.com/Yanghaeun716/BottomNavi
            https://github.com/Yanghaeun716/Main

## 팀 GitHub
    
    https://github.com/mhjoon99/SMU-Time

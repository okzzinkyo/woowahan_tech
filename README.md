# woowahan_tech Repositoriy

작업환경 세팅  __(완료)__ 

  * Create-react-app으로 React typescript 작업환경 설정
  * node.js 설치.

# 기획서
1. 기획적인 확인 사항 .... 무엇을 만들건가? [목표 설정 - 필요!!]
    ### 친구들끼리 문서 공유 서비스
    - 회원 서비스 google 로그인// node 로그인 유지 핸드쉐이크 ( 회원 로그인 정보 백엔드 DB 서버 섹션상태유지 오오스?)
    - 노션 markdown 문서 UI 요소 커버이미지, title, 본문 분리 어떤걸 pick up? >>> 커버 + 제목 분리 나머지 codeblock 이미지 추가.
    - 단일 문서? 하위 폴더? >>> 단일 문서
    - 리소스 퍼블릿 or 프라이빗 >> 친구끼리 공유!!
    - 에디터?? 문서 편집기 개별 컨포넌트(테이블,드래그 앤 드랍, 하이라이트, Map) 
    
    ###### 라이브러리 선택 
    
    ###### 커스터마이징 용이한지, 사람들이 얼마나 쓰고 있는지, 지속적인 관리가 되는지, 사용언어 호환이 되는지, 트렌디한지(당위성 필수!!), 기능이 많은 라이버리가 적절한지?


2. 기술적인 확인 사항
    - 해본적이 없는 기술 난제 도출 // 시간이 얼마나 걸릴지 모름
    - 해본 적 있는 기술 ->  다르게 시도해보고 싶은게 있는지 확인

3. 어떻게 확인 할 건지?  (Plannig)
    - POC (개념 증명 proof of concept 실행가능한지), 프로토타입 (당연히 되는건 아는데 더 유용한, 더 깔끔한 벙법 도모  codepen같은 서비스 사용) 

4. 운영적 확인 사항
    - 서버는 어느 것을 쓸건지 라우팅
    - 개발 환경 설정은?(몇명이서 개발할건지 등) 
    - 개발을 할때 webpack, 다른 build Tool, craTool 등 어느 것을 사용하는지 좋을지.. 
    
      (배포 환경에 따라 변동, 서비스 규모가 커지면 리팩토링 cra 경우, 어느 순간을 벗어나면 너무 해비한 아키택쳐가 된다.)


## 원하는 서비스?


1. 모바일 또는 데스크탑 앱에서 수정시 동기화 버튼 없이 실시간으로 다른 기기로 업로드 
  
    - 실시간 배달 위치나 chat api를 사용하면 될까? <https://pusher.com/channels>

2. 좋아하는 가수 신곡 or 방송활동 알림 서비스. 

    __가수를 등록해놓으면 알림으로 앞으로 예정된 정보를 제공해준다.__
    
    목적: 요즘 코로나 시국으로 공연을 못하는 대신 가수들이 다양한 유투브 컨텐츠나 방송 출연 빈도가 높아지고 있다.
    다 찾아보고 싶은데 너무 많은 컨텐츠가 존재해 방송 이름, 채널, 출연날짜 및 시간을 다 알아내기 힘들고, 본방 사수를 위해 알람을 하나 하나 다 등록까지하기 너무 귀찮다.
    
    
    - 프로그램명, 방송날짜, 발매일 등 정보를 추출해서 알림 기능
    - 원하는 정보가 있는 api 필요
      1. 방송 편성표 <http://211.43.210.44/tvguide/index.php?main=public>
      2. 유트브 스트리밍 검색
      3. 음반, 가수 검색 ex] 멜론 <https://www.apistore.co.kr/generalApi/generalApiView.do?general_service_seq=22>

# Final Project - MuseMarket
SpringBoot + html + thymeleaf + Oracle : 예술 중고 거래 사이트
<br/><br/>

## 🖥️ 프로젝트 개요
**예술품 중고 거래 사이트 : Muse Market**입니다. <br/>
중고 마켓의 매출이 쇼핑 커머스몰 제치며 시장을 키워나가고 있습니다. 소비자가 주체가 되어 사고 파는 중고 판매에 대한 관심으로 시작하여, 중고 마켓의 고급화를 위한 방안에 대해 고민하던 중 예술 분야 관련 중고 거래 사이트인 '뮤즈마켓'을 기획하게 되었습니다. <br/>
음악(악기,LP 등), 미술품, 개인 작품 등을 주요 품목으로 거래하며 커뮤니티 게시판을 통해 예술가들의 전시 정보, 공연 정보를 공유할 수 있습니다. <br/> 마이페이지를 통해 자신이 거래한 품목은 물론이고 커뮤니티에서 사람들과 소통한 내용을 확인할 수 있어, 단순히 거래만 하는 중고 사이트를 넘어 예술을 좇는 개개인들의 소통의 장을 만들고자 했습니다. 


<br/><br/>

## 🕰️ 개발 기간
22.04.28 - 22.05.24 ( 4주 )
<br/><br/>

## 🧑‍🤝‍🧑 맴버구성
 - 팀원1 : 남승은 - DB테이블 설계, ID찾기, PW찾기, 마이페이지 회원정보 수정, CSS, BootStrap
 - 팀원2 : 왕혜민 - 상품 페이지, Ajax 댓글 구현, 마이페이지 회원 정보, Database Script 제작, 전체 통합
 - 팀원3 : 이나영 - 커뮤니티 게시판(CRUD), 1:1문의, 공지사항, 전체 통합
 - 팀원4 : 박가윤 - 메인 페이지, 상품 리스트, 상품 등록, CSS, BootStrap
 - 팀원5 : 양세리 - 로그인, 회원가입
<br/><br/>

## ⚙️ 개발 환경
- `Java 8`
- **IDE** : STS 3.9
- **Framework** : Springboot(2.x)
- **Database** : Oracle DB(11xe)
- **ORM** : Mybatis
<br/>

## 📌 주요 기능

#### 회원가입 및 로그인 - <a href="https://github.com/NamSeungEun/Springboot-project-MuseMacket/wiki/%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85-%EB%B0%8F-%EB%A1%9C%EA%B7%B8%EC%9D%B8" >상세보기 - WIKI 이동</a>
- 회원가입 : ID 중복 체크 및 비밀번호 재확인 
- 로그인  : DB값 검증, 로그인 시 세션(Session) 생성 
- ID찾기, PW찾기 : 클라이언트 DB값 검증 후 정보 제공

#### 메인 및 마이 페이지 - <a href="https://github.com/NamSeungEun/Springboot-project-MuseMacket/wiki/%EB%A9%94%EC%9D%B8-%ED%8E%98%EC%9D%B4%EC%A7%80-%EB%B0%8F-%EB%A7%88%EC%9D%B4-%ED%8E%98%EC%9D%B4%EC%A7%80" >상세보기 - WIKI 이동</a>
- 개인정보 수정 : 클라이언트 DB값 Update
- 마이페이지 : 해당 클라이언트의 판매물품, 찜상품[장바구니], 댓글목록, 커뮤니티에 올린 게시글 등 확인 및 해당 링크로 이동

#### 상품리스트 및 상세 내역 - <a href="https://github.com/Wanghyemin/SpringBootProject-MuseMarket/wiki/%EC%83%81%ED%92%88%EB%A6%AC%EC%8A%A4%ED%8A%B8-%EB%B0%8F-%EC%83%81%EC%84%B8-%EB%82%B4%EC%97%AD" >상세보기 - WIKI 이동</a>
- 상품리스트 : 요청에 따른 상품리스트 추출, BootStrap 활용한 화면 구현
- 상세 내역 : 해당 상품에 대한 데이터 추출, Ajax를 사용한 비동기 댓글 프로그래밍 구현

#### 커뮤니티 및 1:1 문의 - <a href="https://github.com/Wanghyemin/SpringBootProject-MuseMarket/wiki/%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0-%EB%B0%8F-1:1-%EB%AC%B8%EC%9D%98" >상세보기 - WIKI 이동</a> 
- 커뮤니티 : 글 작성, 읽기, 수정, 삭제(CRUD)기능의 게시판
- 1:1 문의 : 회원작성, 관리자 계정만 확인 가능하도록 접근제한

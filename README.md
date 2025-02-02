
Clone AirBnB
-----------------
에어비엔비 클론코딩 하기!
<br/>
다양한 사람들의 맛집까지 공유 할 수 있는 시간!

<br/>

1, 제작기간 & 팀원 소개 🫂
------------------
**- 2022년 02월 11일 ~ 2022년 02년 17일**

  - FE : 김양수, 장혜진, 최연서
  - BE : 강경묵, 오세웅, 진상혁

📍BE 깃허브
https://github.com/G-moog/cloneProject 

📍FE 깃허브
https://github.com/Ryangsu/cloneAirBnB


<br/>
 
2.사용기술  📌
------------------
FE
- React

<br/>
BE
- node.js
- express
- mongo db

<br/>
라이브러리
- aws-sdk: S3 bucket 접근
- cors: Request resource 제한
- dotenv: 환경변수 설정
- joi: 패턴 인증
- JWT: 토큰 생성, 사용자 인증
- mongoose: mongodb model schema
- multer: 이미지 데이터 처리
- multer-S3: 사진 파일 업로드
- S3: AWS bucket

<br/>

3.배포
------------------
- EC2
- AWS S3

4.DB schema
------------------
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/06040c21-1f12-4628-a5da-52d0c6b00742/Untitled.png)

<br/>

5.API
------------------


<br/>

3.실행화면 😄
------------------


<br/>

6.핵심기능🛠
------------------
**메인 페이지**

- 숙소 목록 보여주기 
- 숙소 클릭 시 해당 상세페이지로 전환
- 숙소 리스트 좋아요 기능 
- 숙소 사진 슬라이더 기능
- 버튼 누르면 지도 보여줌 기능
- 지도에 각 위도 경도 마커 표시 
- 카테고리 별로 카드가 다르게 나오는 기능 

**상세페이지**

- 사진은 기본 5장 (50%한장, 12.5%네장)
- 달력 기능 (2개씩 나옴)
- 후기 버튼 누르면 후기 작성 모달 보여주기 
- 모달 내에서 로그인 시 후기 작성 가능 (비 회원은 다시 화면이 뒤로가짐)


**로그인 회원가입 모달**

- 아이디 패스워드는 조건에 맞아야 함
- 아이디와 닉네임 중복 확인이 가능 
- 회원가입이 완료되면 로그아웃으로 바뀜

**게시글 작성 페이지**

- 로그인한 회원만 접근 가능 
- 숙소 이름, 위치, 사진, 가격 작성 가능 
- 이미지는 1장~ 5장까지 가능

**Header /Footer**

- 로그인을 안한경우에는 로그인 회원가입 버튼 노출
- 로그인을 하면 로그아웃 버튼 노출
- 로고클릭시 메인으로 이동 

모든 페이지는 반응형
<br/>

7.트러블 슈팅 😮‍💨
------------------
**지도의 마커표기**
  
  : 지도에 마커를 각 데이터의 위도 경도로 넣었지만 무반응

<br/>
<br/>


8.개인회고 🤫
------------------

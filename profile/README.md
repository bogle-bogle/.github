# THE PET

## 💡 **프로젝트 소개**
**: 개인 맞춤형 반려동물관(더현대닷컴)** <br>
- 기존 더현대닷컴의 반려동물관 리뉴얼을 제안하는 서비스
- 나의 반려동물을 등록하면, 그에 맞춰 상품들을 추천해주는 서비스
- 나의 반려동물이 잘 먹는 사료 성분표를 등록하면, OCR 및 AI를 통해 유사도가 높은 상품들을 추천해주는 서비스
- 나의 반려동물이 알러지가 있는 성분에 주의를 띄워주는 서비스
- 흰디카 예약 서비스

<br>

## 💡 구현 기능

**1. 회원 관련 기능**
- Kakao 연동 회원가입 / 로그인 (OAuth 2.0)
   - 로그아웃

**2. 상품 관련 기능**
   - 상품 목록 필터별 조회 (최신순, 낮은 가격순, 높은 가격순, 할인률순) + 성분 유의사항 표시
   - 상품 상세 조회

**3. 장바구니 관련 기능**
   - 장바구니 조회
     장바구니에 추가
   - 개인 장바구니에서 삭제
   - 개인 장바구니에서 수량 변경

**4. 그룹 장바구니 관련 기능**
   - 그룹 장바구니 생성
   - 그룹 장바구니 내 닉네임 변경
   - 그룹 장바구니에 참여
   - 그룹 장바구니 조회
   - 그룹 장바구니에 추가
   - 그룹 장바구니에서 삭제
   - 그룹 장바구니에서 수량 변경
   - 그룹 장바구니에서 나가기
   - 그룹 장바구니 삭제하기 (그룹장)

**5. 주문 관련 기능**
   - 그룹 장바구니 일괄 주문하기
   - 상세 배송지 검색하기
   - 기본 배송지 입력하기
   - 주문 내역 조회하기

<br>


## 💡 기술 스택
|분류|기술|
| :-: |:- |
|Language|<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"/>  <img src="https://img.shields.io/badge/kotlin-8B00FF?style=for-the-badge&logo=Kotlin&logoColor=white"/> |
|Framework|<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/>  <img src="https://img.shields.io/badge/Android-32DE84?style=for-the-badge&logo=Android&logoColor=white"/> |
|Build Tool|<img src="https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white">|
|DB|<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">|
|Server|<img src="https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black">|
|Collaboration|<img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white">|

<br>


## 💡 **아키텍쳐**
![시스템 아키텍처](https://github.com/chocomochalatte/.github/assets/100582309/13be722c-09c6-4179-86d3-4cfc6f2ea460)

<br>

## 💡 **DB 설계 (ERD)**

![4조-그룹장바구니-erd](https://github.com/chocomochalatte/.github/assets/100582309/2351b813-62bf-4742-9d8b-e68a3398fac5)

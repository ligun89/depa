### Depa 2023.06.17 ~
2023년 제11회 문화데이터 활용 경진대회 공모전_Depa

------------------------------------------------------------

### Description
설명 쏼라 쏼라 ~ 

------------------------------------------------------------

#### 구동 환경 및 필수 세팅
- Python 3.9.6 (default, May  7 2023, 23:32:44)
- Flask 2.3.2
- Werkzeug 2.3.6
- mariadb  Ver 15.1 Distrib 10.11.2-MariaDB  (pip install flask-mysql)

------------------------------------------------------------  
#### 현재 진행 단계

- [x] Enviroment Setting - 2023.06.17

------------------------------------------------------------

##### 소프트웨어 아키텍처 

------------------------------------------------------------

##### 기능 구성도

------------------------------------------------------------
##### Back-end 진행 사항
1. 국립중앙도서관 오픈 API
   1) 사서추천도서검색 API : https://nl.go.kr/NL/search/openApi/saseoApi.do
   2) 소장자료검색 API : https://www.nl.go.kr/NL/search/openApi/search.do
  ==> 두 API 중 택 1 예정
2. DB 테이블 구성
   ERD Cloud 사용하여 테이블 설계 예정 (https://www.erdcloud.com/)
   사용법 : https://inpa.tistory.com/entry/ERD-CLOUD-%E2%98%81%EF%B8%8F-ERD-%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8%EC%9D%84-%EC%98%A8%EB%9D%BC%EC%9D%B8%EC%97%90%EC%84%9C-%EA%B7%B8%EB%A0%A4%EB%B3%B4%EC%9E%90)
3. API 구성
   화면 설계서 및 DB 테이블 고려하여 API 설계
   1) 스터디 Master 테이블
   2) 스터디 Detail 테이블
   3) 도서 Master 테이블
   4) 도서 Detail 테이블
   5) 공통코드 테이블

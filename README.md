# Commento 
5주간의 교육 내용을 정리합니다.

## 1주차
1. 스프링 개발 환경 구축 JDK 설치
    - 환경 변수 설정
    - cmd 창을 통해 셋팅 점검  
2. 스프링 개발 환경 구축 Eclipse, Spring 다운로드 및 설치
3. 스프링 개발 환경 구축 톰캣 설정
4. 스프링 개발 환경 구축 Hello World 페이지
5. mariadb, mysql Workbench 설치 및 샘플 DB 구축
    - mariadb 설치 및 실행
    - workbench 설치 및 스키마 작성
6. 스프링, Mariad, MyBatis 연동, 데이터 조회
    - 각 파일을 수정 및 추가하여 Spring, Mariad, MyBatis를 연동하고 조회하였다.
![image](https://user-images.githubusercontent.com/77236420/105247169-afb5c480-5bb7-11eb-9804-38b1a1df281c.png)
------
## 2주차
1. SW활용률 API 가이드 작성
    - 접속자 수
    - 부서별 접속자 수
    - 로그인 요청 수
    - 게시글 작성 수
2. 요청 url, 요청 parameter, 응답 데이터 포맷을 고려
3. 공공 데이터 API 문서 및 제공된 인터페이스 가이드를 참고

[2주차_SW 활용 현황 API 가이드 문서_김덕현.docx](https://github.com/DEOKHYEONKIM/Spring/files/5845595/2._SW.API._.docx)
------
## 3주차
1. RestController를 활용한 간단 API 구현
2. 스프링부트 개발 환경 셋팅
    - 기본 test 진행
![3주차_1](https://user-images.githubusercontent.com/77236420/106096045-25053480-6178-11eb-9cdc-0de5c9fa738c.PNG)
3. 통계 API(SW활용현황)을 위한 DB, TABLE 생성
4. [20년도 로그인 수 API] 스프링부트, mybatis, mariadb 연동
![3주차_2](https://user-images.githubusercontent.com/77236420/106096074-31898d00-6178-11eb-929c-ad23830896e3.PNG)

------
## 4주차
1. API 구축을 위한 아래 SQL 작성
2. RestController를 활용하여 Rest API를 구축합니다.
3. 통계 API 구축 SQL 작성
    * MySQL Workbench Table
        - user
        ![4주차_user](https://user-images.githubusercontent.com/77236420/106891207-bf8fe580-672d-11eb-8d9d-a215e35ee822.PNG)
        - requestinfo
        ![4주차_requestinfo](https://user-images.githubusercontent.com/77236420/106891215-c0c11280-672d-11eb-8eb3-a2941a729dde.PNG)
    
    - 월별 접속자 수
    ![4주차_월](https://user-images.githubusercontent.com/77236420/106891236-c6b6f380-672d-11eb-80e2-40ba17f00009.PNG)
    
    - 일자별 접속자 수
    ![4주차_일](https://user-images.githubusercontent.com/77236420/106891241-c7e82080-672d-11eb-9801-66265c368c7a.PNG)
    
    - 평균 하루 로그인 수
    ![4주차_평균로그인](https://user-images.githubusercontent.com/77236420/106891249-c9b1e400-672d-11eb-8e7d-052f64843f4a.PNG)
    
    - 휴일을 제외한 로그인 수
    ![4주차_휴일제외](https://user-images.githubusercontent.com/77236420/106891258-cb7ba780-672d-11eb-8fe1-1c4d50d60796.PNG)
    
    -부서별 월별 로그인 수
    ![4주차_부서별](https://user-images.githubusercontent.com/77236420/106891230-c4ed3000-672d-11eb-8a08-e2d794e0df92.PNG)

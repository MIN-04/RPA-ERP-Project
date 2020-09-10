# RPA-ERP-Project
[AJ네트웍스] 인턴 과제 : AA, 전자정부프레임워크를 이용한 RPA / 가상 ERP 웹 프로젝트 (프로젝트 기간 : 2020.06 - 2020.07)
  
### 0. 목차
+ 프로젝트명 / 팀원
+ 담당업무
+ 개발환경
+ 개발 일정
+ 개발아키텍쳐 : MVC
+ 프로젝트 Work Flow
+ 프로젝트 화면 구성
+ 요구사항정의서
+ 시연 동영상
  
### 1. 프로젝트명 / 팀원
    - RPA 및 가상 ERP / 개인
   
### 2. 담당업무
    - 1) 가상 ERP
        - 1.1) 로그인 / 로그아웃 : 세션을 사용하여 로그인, 로그인 실패 시 로그인 화면으로 리다이렉트. 로그아웃 시 로그인 화면으로 돌아간다.
        - 1.2) 파일 업로드 : 엑셀 파일(.xlsx, .xls)을 업로드하여 파일 데이터를 읽고, DB에 데이터를 저장한다. 
        - 1.3) 파일 조회 : 입력한 파일의 데이터를 DB에서 읽어와 목록으로 보여준다. 
    - 2) RPA
        - 2.1) 다음 메일 로그인
        - 2.2) 내게 쓴 메일함 들어가기
        - 2.3) 엑셀 파일이 첨부된 메일 제목 검색
        - 2.4) 엑셀 파일을 바탕화면에 저장
        - 2.5) 가상 ERP 프로그램 실행
        - 2.6) 로그인
        - 2.7) 바탕화면에 다운받은 엑셀 파일 업로드
        - 2.8) 업로드한 파일 데이터 조회
        
### 3. 개발환경
    - OS            :   Windows 10 pro
    - JDK           :   Java SE 8 (Oracle JDK 1.8)
    - Tools         :   전자정부프레임워크 3.9.0 / Automation Anywhere
    - Server        :   Apache Tomcat 9.0
    - 라이브러리    :   Apache POI / Apache Commons FileUpload
    - Front-end     :   JavaScript / Jquery / JSP / Html5 / Bootstrap / CSS
    - Back-end      :   Java / Servlets / MySQL / JSP

### 4. 개발 일정
![AJ_개발일정.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A0%95.PNG "AJ_개발일정.PNG")   
  
### 5. 개발아키텍쳐 : MVC
![RPA 및 가상 ERP_MVC](https://github.com/MIN-04/SistAirlines-Project/blob/master/SistAirLine/doc/SistAirlines_MVC.png "RPA 및 가상 ERP_MVC.png")  

### 6. 프로젝트 Work Flow
![AJ_workflow.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_workflow.PNG "AJ_workflow.PNG") 

### 7. 프로젝트 화면 구성
1. 가상 ERP
    + Login Page  
    
    ![AJ_로그인화면.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%94%EB%A9%B4.PNG "AJ_로그인화면.PNG")
      
    + FileUpload Page  
    
    ![AJ_파일업로드화면.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%ED%8C%8C%EC%9D%BC%EC%97%85%EB%A1%9C%EB%93%9C%ED%99%94%EB%A9%B4.PNG "AJ_파일업로드화면.PNG")
    
    + FileUpload 결과  
    
    ![AJ_파일업로드결과.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%ED%8C%8C%EC%9D%BC%EC%97%85%EB%A1%9C%EB%93%9C%EA%B2%B0%EA%B3%BC.PNG "AJ_파일업로드결과.PNG")
    
2. RPA
    + RPA 코드 
    
    ![RPA_코드_1.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/%5B%EC%9D%B8%ED%84%B4_%EA%B9%80%EB%AF%BC%EC%A7%80%5DRPA_%EC%BD%94%EB%93%9C_1.PNG "RPA_코드_1.PNG")
    ![RPA_코드_2.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/%5B%EC%9D%B8%ED%84%B4_%EA%B9%80%EB%AF%BC%EC%A7%80%5DRPA_%EC%BD%94%EB%93%9C_2.PNG "RPA_코드_2.PNG")
    ![RPA_코드_3.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/%5B%EC%9D%B8%ED%84%B4_%EA%B9%80%EB%AF%BC%EC%A7%80%5DRPA_%EC%BD%94%EB%93%9C_3.PNG "RPA_코드_3.PNG")
    
### 8. 요구사항정의서
    + 가상 ERP
    
    ![AJ_요구사항분석_ERP.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EB%B6%84%EC%84%9D_ERP.PNG "AJ_요구사항분석_ERP.PNG")
    
    + RPA
    
    ![AJ_요구사항분석_RPA.PNG](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EB%B6%84%EC%84%9D_RPA.PNG "AJ_요구사항분석_RPA.PNG")

### 9. 시연 동영상
[![RPA-ERP](https://github.com/MIN-04/RPA-ERP-Project/blob/master/doc/AJ_%EB%A1%9C%EA%B7%B8%EC%9D%B8%ED%99%94%EB%A9%B4.PNG)](https://youtu.be/vMZmKv1e_d0)


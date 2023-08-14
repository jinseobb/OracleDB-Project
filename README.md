> # OracleDB Project - Center Management System
Oracle DB와 sql developer를 활용해 진행한 교육센터 시스템 관리 프로젝트 입니다.   
<br/>


> ## 🖥 프로젝트 소개
교육 센터를 운영함에 있어 필요한 제반 기능들을 하나의 프로그램으로 관리하기 위해 진행한 프로젝트

교육센터 제반 기능의 통합적 관리, 네트워크 활성화, 계정별 기능 이용의 편의성을 증진시켜 관리를 더욱 쉽게 할 수 있도록 구현하였습니다.  
<br/>



> ## 📅 개발기간
* 23.03.27일 ~ 23.04.07일 
<br/>
  
> ## ⚙ 개발 환경
- **IDE** : SQL Developer
- **Database** : Oracle DB(11xe)  
* `EXERD`

  
### ✔️Back-end
<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
</br>

</br>

> ## :keyboard:DB 설계
<img width="1500px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/7d4567ba-d2ba-4304-9122-0924e3193399"/> 

</br></br>


### 📌 주요 기능  
<br/>

##  공통기능

> ### 메인 화면
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/f664100c-d7fb-4a7d-b31e-336ff1192336"/>
  
### 📋 구현 기능  
* 메인 화면으로 관리자, 고객 중 원하는 계정으로 로그인 할 수 있는 페이지입니다.

<br/>

## 관리자
#### 💡 관리자는 카드, 상품, 대출 중 원하는 상품을 선택 후 해당 상품의 목록 조회, 상세보기, 추가, 삭제가 가능합니다. 
#### *모든 상품의 추가, 삭제 방법은 동일합니다.
<br/>

> ### 교사 계정 관리 페이지

#### - 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/088059ab-9576-42a9-b5ba-38033ceeb81d"/>
<br/>

#### - 교사 계정 목록
<img width="350px"  src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/ed26b04e-3f96-435a-a995-b7b997cbdab5"/>  
<br/>  

#### - 프로시저 호출
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/62adf45d-c455-4add-a0ee-4dbccd049f16"/>
<br/>  

#### - 교사 계정 업데이트 후 목록
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/1d8e535e-1e11-4f62-bea1-be23eeb1f7ca"/>
<br/>  

#### - 유효성 검사 실패에 따른 업데이트 실패
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/69f144d0-dd6f-4a8c-a5aa-56f5d710b029"/>
<br/>
  
### 📋 구현 기능  
* 관리자가 교사 계정 정보를 추가하는 기능입니다.
* 교사의 아이디, 주민등록번호, 연락처, 이름을 올바르게 입력하면 저장 함수의 반환값인 ‘입력되었습니다.’ 문구가 출력되고 데이터가 삽입됩니다.
* 만약 자료형이 틀리는 등의 오류가 있을 경우 예외처리를 통해 ‘입력에 실패하였습니다.’ 문구가 출력되고 데이터가 삽입되지 않습니다.
  




<br/>

> ### 수료 날짜 지정 페이지

#### - 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/6dac18e0-cf1a-4890-b5b6-d7e0dba8e568"/>
<br/>

#### - 수료날짜 지정 전 목록
<img width="350px"  src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/ed26b04e-3f96-435a-a995-b7b997cbdab5"/>  
<br/>  

#### - 수료날짜 지정 중
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/1e4c8f66-34bb-44af-b562-6428116f38d9"/>
<br/>  

#### - 수료날짜 지정 후 목록
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/e22df3ef-e2bf-439b-8ab5-3c718a2952dc"/>
<br/>
  
### 📋 구현 기능  
* 한 과정이 끝난 후 수료 날짜를 지정하는 기능입니다.
* 관리자가 update문으로 과정번호를 입력하여 수료 상태를 ‘졸업’으로 바꿀 때, 트리거를 이용해 해당 학생이 들은 과정의 종료일을 학생의 수료일로 지정합니다.



<br/>

> ### 카드 상품 목록 페이지

#### - 카드 종류 선택
<img width="250px" src="https://github.com/jinseobb/Banking-project/assets/131458472/0be7e215-223e-405e-86de-d6e0671c32a0"/>  
<br/>

#### - 목록
<img width="350px" src="https://github.com/jinseobb/Banking-project/assets/131458472/37d064e7-ab61-4563-bd4d-28cd00c7dd0b"/>  
<br/>

#### - 상세 보기
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/ea8c9472-7e06-4fa6-99b8-65dfbfc5618c"/>
   
### 📋 구현 기능  
* 현재 서비스 중인 카드상품의 목록을 조회 할 수 있는 페이지 입니다.(신용카드, 체크카드 별로 조회 가능)
* 원하는 상품의 번호를 입력하면 해당 상품의 상세 정보를 확인 할 수 있습니다.
  

<br/>

## 교사
#### 💡 고객 카드, 상품, 대출 중 원하는 상품을 선택 후 해당 상품 목록 조회 및 추천이 가능하고, 가입된 상품 조회가 가능합니다. 
#### *모든 상품의 조회 및 추천 방법은 동일합니다.
<br/>

> ### 교육생 출결 조회 페이지

#### - 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/6f8d8229-2359-4a51-9fc6-20d756f5df19"/>
<br/>

#### - 교육생 출결 목록
<img width="350px"  src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/bccc0b3f-f877-4e2c-b4d0-3671034821b3"/>  
<br/>  

#### - 프로시저 호출
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/bc7c23e6-eeec-408b-ba13-15c0904477bd"/>
<br/>  

#### - 과목번호, 교육생 번호에 따른 출결 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/118cb137-4380-4264-961d-9ba948018d56"/>
<br/>  

#### - 출결 최종 결과
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/737aec6f-0d03-4e63-9467-4862e6af1e00"/>
<br/>
  
### 📋 구현 기능  
* 과목 번호, 교육생 번호에 따른 출결 정보를 출력합니다.
* 

> ### 카드 

#### - 카드 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/840d5920-0d66-4e79-a31e-f84bb502f700"/>
  
### 📋 구현 기능  
* 고객이 본인의 소비 패턴에 맞는 새로운 카드(신용카드, 체크카드) 를 추천 받을 수 있는 페이지 입니.
<br/>

> ### 대출

#### - 대출 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/d928683f-1ab7-49bc-96ce-c18b298cdbf2"/>
<br/>

#### - 신용 대출 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/c8146e90-ac1f-4e1f-925c-f92246eaf304"/>
<br/>

#### - 대출 계산기 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/be5df517-a270-4e89-9822-17c7e052c884"/>
<br/> 
 
### 📋 구현 기능  
* 고객이 신용대출, 자동차 대출, 전 월세 반환보증 대출 중 가입하고 싶은 종류의 대출을 선택 후 추천 받을 수 있습니다.
* 고객이 대출 계산기를 활용하여 본인이 받을 대출에 대한 사전 계산을 할 수 있습니다.


<br/>

> ### 적금

#### - 적금 추천 페이지
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/fd640a69-2dfd-4be8-914e-2f90767c8a3b"/>  
<br/>

#### - 적금 계산기 페이지 (매일 일정 금액을 저축할 때)
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/38d1537b-3047-4102-b3e5-6e7fb51f8a07"/>  
<br/>

#### - 적금 계산기 페이지 (목표 금액을 만들 때)
<img width="550px" src="https://github.com/jinseobb/Banking-project/assets/131458472/de4c623b-f16c-4654-84d8-32e6afe6bc5b"/>  
<br/>

### 📋 구현 기능  
* 고객이 현재 이벤트 진행중인 적금 상품을 확인 할 수 있습니다
* 고객이 적금 계산기를 활용하여 본인이 받을 적금에 대한 사전 계산을 원하는 목표 별로 계산 할 수 있습니다.



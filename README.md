> # OracleDB Project - Center Management System
Oracle DB와 sql developer를 활용해 진행한 교육센터 시스템 관리 프로젝트 입니다.   
<br/>


> ## 🖥 프로젝트 소개
교육 센터를 운영함에 있어 필요한 제반 기능들을 하나의 프로그램으로 관리하기 위해 진행한 프로젝트

교육센터 제반 기능의 통합적 관리, 네트워크 활성화, 계정별 기능 이용의 편의성을 증진시켜 관리를 더욱 쉽게 할 수 있도록 구현하였습니다.  
<br/>



> ## 📅 개발기간
* 23.03.27 ~ 23.04.07  
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


## 관리자
#### 💡 통합 관리자 기능입니다.

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


## 교사
#### 💡 교사 기능입니다.
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
<br/>
  

> ### 교육생 취업률 조회 페이지

#### - 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/407bb00a-9ca8-47c9-a8f3-2cc804a02fb9"/>  
<br/>  

#### - 취업률 조회 호출 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/d8cd4313-c7ab-4931-81a1-5ac3c17d7059"/>  
<br/>  

#### - 취업률 조회
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/a4eca4d2-f8d4-47ff-9e9d-b1cc2c9c2b8a"/>  
<br/>

  
### 📋 구현 기능  
* 교사가 각 과정별 교육생들의 취업률을 조회할 수 있는 기능을 프로시저로 구현했습니다.
* 선언부에서 과정번호를 매개변수로 선언하고, 취업률을 지역변수로 선언 한 뒤
  실행부에서 교육생의 수강여부가 = 'Y'인 교육생의 개수를 구한뒤 이를 토대로 취업률을 계산하는 코드를 실행하게끔
  프로시저를 구현했습니다.
* 호출코드에서 조회하고 싶은 과정 번호를 입력하면 해당 과정의 취업률이 출력됩니다.


<br/>  

## 교육생
#### 💡 교육생 기능입니다.
<br/>

> ### 교육생 로그인 페이지

#### - 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/e1de70a6-0788-4c61-a69b-b0d7fdb48f129"/>  
<br/>
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/b402aaaa-de60-4ad1-9d56-8e49d6872358"/>
<br/>

#### - 로그인 호출 코드
<img width="350px"  src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/cf82081a-e795-47a1-8f42-e20babefd018"/>  
<br/>  

#### - 마이페이지(로그인 완료)
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/c2338611-77ea-429f-852f-146f180edf4a)"/>
<br/>  

  
### 📋 구현 기능  
* 과목 번호, 교육생 번호에 따른 출결 정보를 출력합니다.
<br/>
  

> ### 교육생 일별 출결 조회

#### - 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/59548450-1fc9-45e9-8830-c70ea8d5ae8e"/>    
<br/>  
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/67d11afd-08dd-4c67-8768-babeac933700"/>    
<br/>  

#### - 일별 출결 호출 코드
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/421225fd-629a-4f6a-b7a7-d9f0553d38eb)"/>  
<br/>  

#### - 일별 출결 결과
<img width="350px" src="https://github.com/jinseobb/OracleDB-Project/assets/131458472/d007e31f-0bbf-4052-a402-9b603e30a31f"/>  
<br/>

  
### 📋 구현 기능  
* 교육생이 본인의 입/퇴실 시간을 조회할 수 있는 기능을 프로시저로 구현했습니다.
* 선언부에서 날짜와 교육생번호를 매개변수로 선언한 후
 실행부에서 커서를 통해 매개변수로 입력받은 날짜 및 교육생번호와 일치하는 항목을 찾도록 구현했습니다.
* 호출코드에서 조회하고자 하는 날짜와 교육생 본인의 번호를 입력하면 해당 날짜의 입/퇴실 시간이 출력됩니다.

<br/>




> # Spring Project - BookBBang
스프링을 활용하여 제작한 도서 통합 서비스 프로그램  
<br/>

> ## 🖥 프로젝트 소개
도서 구매 사이트가 아닌 커뮤니티, 중고거래 등 다양한 기능을 활용 할 수 있는 도서 통합 서비스 플랫폼.  

개개인의 취향에 맞는 도서 추천, 서평을 통해 해당 도서에 대한 세부 정보 습득, 중고거래를 통해 합리적인 도서 구매 등 도서에 관한 여러 서비스를 제공합니다.  
<br/>


> ## 📅 개발기간
* 23.06.19일 ~ 23.07.12일  
<br/>
  
> ## ⚙ 개발 환경
* `Java 8`
* `JDK 1.8.0`
- **IDE** : STS3
- **Database** : Oracle DB(11xe), MyBatis  

### ✔️Frond-end
<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/Css-1572B6?style=for-the-badge&logo=Css3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
### ✔️Back-end
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
</br>

</br>

> ## :keyboard:DB 설계
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/54098fe7-ae84-428c-aa36-276f7569bff2" width="550" height="400"/> 

</br></br>

### 📌 주요 기능
> 메인 화면
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/70d214e9-6bc9-43eb-a42a-0519c4eeeb43"/>
  
📋 구현 기능  
* 메인 화면으로 신작, 베스트 셀러 등 분야별 대표 도서 목록이 출력됩니다.

<br/>

> 도서 목록 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/9b49544e-39a7-4b95-abe9-a46022979dd0"/>
  
📋 구현 기능  
* 메인 페이지에서 도서 탭을 클릭시 도서 페이지로 이동, 메인 페이지에서는 책을 대분류, 소분류로 나눠 목록을 출력, 낮은 가격순, 높은 가격순, 출판날짜 등으로 정렬하여 조회가 가능합니다.

<br/>

> 도서 상세정보, 구매 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/9038c98c-d4ad-43a5-a2be-420f242c5ece"/>
  
📋 구현 기능  
* 선택한 도서의 상세 정보를 확인 할 수 있고, 장바구니에 넣기 또는 바로 주문이 가능합니다.

<br/>

> 장바구니 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/a45acee6-f70d-489f-94a5-a6bcec1c0800"/>
  
📋 구현 기능  
* 구매 페이지에서 장바구니에 담기 버튼을 누르면 장바구니에 해당 도서 상품이 담깁니다.
* 장바구니 상품 중 원하는 상품만 구매, 삭제가 가능합니다.

<br/>

> 주문 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/3a919ba6-d091-4524-9e44-c762d969e4de"/>
  
📋 구현 기능  
* ajax를 활용하여 원하는 배송지를 선택하면 실시간으로 배송지 정보가 변합니다.
* ajax를 활용하여 실시간으로 쿠폰을 적용시켜 할인된 금액이 출력됩니다.
* 카카오결제 api를 활용하여 카카오페이 결제가 가능합니다.

<br/>

> 커뮤니티 '북유럽'의 메인 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/dd19de8d-cb4d-418a-9ed1-9e3d10b05e17"/>
  
📋 구현 기능  
* 소비자들이 작성한 서평 중 이달의 서평 어워드에 선정된 서평 목록이 한눈에 보기 쉽도록 도서 표지가 출력됩니다.

<br/>

> '북유럽'의 서평 목록 출력 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/de8a8ba5-5009-49ee-b924-3395ce3e0170"/>
  
📋 구현 기능  
* 서평 목록 페이지에선 도서 표지만 출력되는것이 아닌 책의 기본 정보들모두 출력되어 서평에 대한 정보가 더욱 상세하게 출력됩니다.


<br/>

> 매장별 위치 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/26d0b1fe-3505-4911-a8a3-f066d8c8358c"/>
  
📋 구현 기능  
* 카카오맵 api를 활용하여 오프라인 매장의 위치가 지도에 출력합다.


<br/>

> 마이페이지 > 주문 내역 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/a7df850f-f8c2-477a-ae66-2443fd324fe1"/>
  
📋 구현 기능  
* 주문 내역이 한 눈에 알아보기 쉽게 출력됩니다.
* ajax를 활용하여 주문 취소 버튼을 클릭할 때 주문 접수 카운트가 줄어들고 취소 카운트가 늘어납니다.

<br/>

> 마이페이지 > 배송 주소록 페이지
<img width="550px" src="https://github.com/jinseobb/BookBBang/assets/131458472/076c6401-4197-423a-b8f2-ed8e12c76757"/>
  
📋 구현 기능  
* 주소 api를 활용하여 주소 등록을 더욱 편리하게 구현하였습니다.
* ajax를 활용하여 실시간 배송지 CRUD가 가능합니다.

<br/>

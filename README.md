<p align='center'>
    <img src="https://capsule-render.vercel.app/api?type=venom&height=300&color=FFDC00&text=GIGA%20COFFEE&textBg=false&animation=fadeIn&fontColor=452613&fontSize=80&reversal=false&desc=기억%20속,%20가장%20맛있었던%20한%20모금&descAlignY=80"/>
</p>

### 프로젝트 기본 소개

---
내용
<br><br>

### 프로젝트 배경

---
내용
<br><br>

### 기술 스택

---
내용
<br><br>

### 사용자 별 시나리오

---

## 1 ) 시나리오

<br>

> 가맹점 관리자는 다음과 같은 기능을 가지고 있다.

<br>

&nbsp;　**1. 가맹점 관리자는 Email, Password, 이름 등을 입력하여 회원가입이 가능하다.**

&nbsp;　**2. 가맹점 관리자는 회원가입 시 입력한 ID 와 PW를 통해 로그인이 가능하다.**

&nbsp;　**3. 가맹점 관리자는 재고가 부족한 상품을 주문할 수 있다.**

&nbsp;　**4. 가맹점 관리자는 자신의 매장에 필요한 상품을 검색할 수 있다.**

&nbsp;　**5. 가맹점 관리자는 현재 매장에 있는 제품들의 재고를 확인하고 수정할 수 있다.**

&nbsp;　**6. 가맹점 관리자는 자신의 주문 내역을 조회할 수 있다.**

&nbsp;　**7. 가맹점 관리자는 문의사항을 작성할 수 있다.**

&nbsp;　**8. 가맹점 관리자는 공지사항을 확인할 수 있다.**

<br> <br>

> 본사 관리자는 다음과 같은 기능을 가지고 있다.

<br>

&nbsp;　**1. 본사 관리자는 지급 받은 Email, Password를 통해 로그인이 가능하다.**

&nbsp;　**2. 본사 관리자는 일일/월별 매출 추이 그래프와 발주 총액 표를 확인할 수 있다.**

&nbsp;　**3. 본사 관리자는 재고 현황 그래프와 가맹점 별 발주액 표를 확인할 수 있다.**

&nbsp;　**4. 본사 관리자는 가맹점들의 정보를 조회할 수 있다.**

&nbsp;　**5. 본사 관리자는 가맹점들이 주문한 주문 내역들을 확인할 수 있다.**

&nbsp;　**6. 본사 관리자는 상품을 등록하고 수정할 수 있다.**

&nbsp;　**7. 본사 관리자는 창고를 등록할 수 있다.**

&nbsp;　**8. 본사 관리자는 창고들의 목록을 조회할 수 있고 창고 별 상품 재고 조회를 할 수 있다.**

&nbsp;　**9. 본사 관리자는 가맹점 관리자가 작성한 문의사항에 답변을 작성할 수 있다.**

&nbsp;　**10. 본사 관리자는 공지사항을 작성할 수 있다.**

<br><br>

### 프로젝트 설계

---
[ERD]<img src="./img/final_erd.png">
<br><br>

[[릴레이션 스키마]<img src="./img/final_relation.png">]
<br><br>

<br><br>

### API

---

[[API 명세서](https://www.notion.so/API-3680b3a4d3b641108f2686515dfc2222)]
<br><br>

<br><br>

### API 테스트 결과 (Post Man)

---
<br>

<details><br>
<summary><b span style="font-size: larger;">본사 관리자</b></summary>
    <div>
         <details>
         <summary><b>B_MANAGER_001. 본사 회원가입</b></summary>
         <br>
         <p><b>➡ 본사 관리자가 [ Id, Password, Email, 이름, 핸드폰 번호, 부서명을 입력하여 회원가입을 한다.<br>
	 </b></p><br>
         <p><img src=""/></p>
         </details><br>
	    
	 <details>
         <summary><b>B_MANAGER_002. 본사 로그인</b></summary>
                  <br>
         <p><b>➡ 관리자가 브랜드에서 요청 시, 요청한 내용으로 브랜드 정보를 수정한다.</b></p><br>
         <p><img src="https://github.com/beyond-sw-camp/be02-2nd-developer_passion-fashion/assets/148875644/8c9bba8e-b0cc-4e2d-8839-a7f2854f7dc6"/></p>
         </details><br>
	 
	 <details>
         <summary><b>REQ-0003. 브랜드 목록 조회</b></summary>
                  <br>
         <p><b>➡ 관리자가 등록된 브랜드의 목록을 조회한다.</b></p><br>
         <p><img src="https://github.com/beyond-sw-camp/be02-2nd-developer_passion-fashion/assets/148875644/f3f889f4-9400-4271-85b8-cfc6beddc9e0"/></p>
         </details><br>
	 
	 <details>
         <summary><b>REQ-0004. 특정 브랜드 조회</b></summary>
                  <br>
         <p><b>➡ 관리자가 브랜드 IDX를 통해 특정 브랜드의 정보를 조회한다.</b></p><br>
         <p><img src="https://github.com/beyond-sw-camp/be02-2nd-developer_passion-fashion/assets/148875644/d138362e-fa5f-4e23-a044-44eb7278c97d"/></p>
         </details><br>
	 <details>
         <summary><b>REQ-0005. 회원 리스트 조회</b></summary>
                  <br>
         <p><b>➡ 관리자가 전체 회원의 목록을 조회한다.</b></p><br>
         <p><img src="https://github.com/hyungdoyou/LONUA_Project/assets/148875644/c25eb7e4-e46c-4baf-b76d-93e68819c4c6"/></p>
         </details><br>
    </div>
</details>

<br>

<details><br>
<summary><b span style="font-size: larger;"> 가맹점 관리자</b></summary>
<div>
         <details>
         <summary><b>B_MANAGER_001. 회원가입</b></summary>
         <br>
         <p><b>➡ 관리자가 [ 브랜드명, 브랜드 소개, 브랜드 이미지, 브랜드 스타일, 사업자 주소, 전화번호, 사업자 등록번호, 은행 계좌 번호,<br>
&nbsp;&nbsp;&nbsp;　전화번호, 환불 주소, 환불 비용, 환불 택배사 ] 를 입력하여 브랜드를 등록한다.</b></p><br>
         <p><img src="https://github.com/beyond-sw-camp/be02-2nd-developer_passion-fashion/assets/148875644/2cf3060d-106d-4c19-94ab-62586f6f164a"/></p>
         </details><br>
</div>

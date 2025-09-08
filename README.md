# 🏢 MicroSonic ERP  

**안현준**  

**MicroSonic ERP**는 기업의 **재무, 인사, 자산, 영업, 금융, 재고 관리**를 통합적으로 제공하는 ERP 시스템입니다.  
Spring Boot 기반으로 REST API를 제공하며, React 프론트엔드와 연동되어 **실시간 데이터 관리**가 가능합니다.  

---

## 📅 개발 기간  

- 전표 관리: 2025.08.18 ~ 2025.08.28 [전표 기능 영상 보기](https://youtu.be/-20GCA1JWpw)
- 나머지 기능: 추후 개발 예정  

---

## ⚙️ 기술 스택  

![Java21](https://img.shields.io/badge/Java21-5382a1?style=for-the-badge&logo=openjdk&logoColor=white) ![SpringBoot3.4.8](https://img.shields.io/badge/SpringBoot3.4.8-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Bootstrap5](https://img.shields.io/badge/Bootstrap5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white) ![JavaScriptES6](https://img.shields.io/badge/JavaScriptES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🗂️ 프로젝트 설명  

### 📌 현재 구현된 기능  

#### 💰 회계 관리 (Accounting)  
- 전표 관리 [전표 기능 영상 보기](https://youtu.be/-20GCA1JWpw)

### 📌 추후 개발 예정  

- 로그인 및 권한 관리 (Spring Security)  
- 재고 관리  
  - 품목 관리  
  - 재고 관리  
- 영업 관리  
  - 견적서 관리  
  - 수주서 관리  
  - 거래처 관리  
- 금융 관리  
  - 회사 자산 관리  
  - 입출금 내역 관리  
  - 이체 관리  
  - 미수금 관리  
- 인사 관리  
  - 조직도 관리  
  - 급여 기준 정보 관리  
  - 복리후생 등록  

---

## 📂 프로젝트 구성  

<details>
<summary>전표 기능 ERD</summary>  

![전표기능 ERD](./images/transaction_erd.png)

</details>  

<details>
<summary>프로세스 정의</summary>  

![프로젝트 정의1](./images/process1.png)
![프로젝트 정의2](./images/process2.png)
![프로젝트 정의3](./images/process3.png)

</details>  

---

## 🎬 실행 화면  

<details>
<summary>실행 화면 보기</summary>

<details>
<summary>전표 화면</summary>

### 전표 리스트
![전표 리스트](./images/transactionList.gif)

### 전표 리스트 검색
![전표 리스트 검색](./images/transactionListSearch.gif)

### modal창을 이용한 데이터 기입
![modal창을 이용한 데이터 기입](./images/modal.gif)

### 제품 정보 추가
![제품 정보 추가](./images/transaction_item.gif)

### 분개 추가
![분개 추가](./images/transaction_record.gif)

### 전표 작성
![전표 작성](./images/transaction_insert.gif)

### 전표 자세히 보기
![전표 자세히 보기](./images/transaction_view.gif)

### 수정으로 Row 삭제
![수정으로 Row 삭제](./images/transaction_edit_delete_item.gif)

### 멀티파일 업로드
![멀티파일 업로드](./images/transaction_multifile.gif)

### 파일 다운로드
![파일 다운로드](./images/transaction_file_download.gif)

### 전표 삭제
![전표 삭제](./images/transaction_delete.gif)

</details>

</details>


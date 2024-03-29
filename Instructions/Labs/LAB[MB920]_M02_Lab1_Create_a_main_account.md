---
lab:
  title: '랩 1: 기본 계정 만들기'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# 모듈 2: Microsoft Dynamics 365 Finance의 기본 사항 알아보기

## 랩 1: 기본 계정 만들기

## 랩 설정

   - **예상 시간:** 5분

## 지침


1.  **Finance and Operations 홈** 페이지 오른쪽 위에서 작업을 수행할 회사가 **USMF**인지 확인합니다.

2.  필요한 경우 회사를 선택하고 메뉴에서 **USMF**를 선택합니다.
3.  왼쪽 탐색 창에서 **모듈 > 총계정원장 > 달력 > 회계 달력**를 선택합니다.
4.  달력으로 **회계**를 선택합니다.
5.  현재 역년을 이미 생성했다면 **회계 달력** 페이지를 종료합니다.
6. 현재 역년을 생성하지 않았다면 작업 창에서 **새 연도** 단추를 선택하고 다음 스크린샷과 같이 현재 연도를 입력합니다. **만들기 단추**를 선택하여 현재 연도의 달력을 생성합니다.

![회계 달력에서 새 연도를 생성하는 방법이 나와 있는 스크린샷](./media/lab-create-a-main-account-04.png)


4.  왼쪽 탐색 창에서 **모듈** > **총계정원장** > **계정 차트** > **계정** > **기본 계정**을 선택합니다.

5.  작업 창에서 **+ 새로 만들기**를 선택합니다.

6.  **기본 계정** 페이지에 다음 값을 입력합니다.

    - 기본 계정: **601510**

    - 이름: **국제 전화 요금**

    - 기본 계정 유형: **경비**

    - 기본 계정 범주: **TANDEEXP**

    - DB/CR 기본값: **직불**

    ![기본 계정 - 계정 차트: 공유 페이지(다양한 값을 추가해야 함)가 나와 있는 스크린샷](./media/lab-create-a-main-account-01.png)

7.  **모듈 &gt; 총계정원장 &gt; 분개장 기입 &gt; 일반 분개장**으로 이동합니다.

8.  작업 창에서 **+ 새로 만들기**를 선택합니다.

9.  **일반 분개장** 페이지에서 다음 값을 입력하고 작업 창에서 **라인**을 선택합니다.

    - 이름: GenJrn

10.  **분개장 바우처** 페이지에서 다음 값을 입력합니다.

    - 계정 유형: **원장**

    - 기본 계정: **601510**

    - 직불: **10.00** 

    - 상쇄 계정 유형: **원장**

    - 상쇄 계정 번호: **110180** 

11. 작업 창에서 **저장** 단추를 선택합니다.

12. **유효성 검사 &gt; 게시 시뮬레이션**을 선택합니다. 

13. 작업 창에서 **게시** 단추를 선택합니다. 분개장이 게시됩니다.

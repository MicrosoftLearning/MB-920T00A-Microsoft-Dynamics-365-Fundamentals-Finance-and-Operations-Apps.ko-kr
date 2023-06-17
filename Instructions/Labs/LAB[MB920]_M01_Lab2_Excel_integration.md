---
lab:
  title: '랩 2: Excel 통합'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# 모듈 1: Dynamics 365 금융 및 운영 앱의 핵심 기능 살펴보기

## 랩 2: Excel 통합

## Objective

이 랩에서는 Dynamics Data Connector Office 추가 기능 앱을 사용하여 재무 및 운영에서 Excel로 데이터를 복사하는 방법을 알아봅니다. 또한 동일한 앱을 사용하여 Dynamics 365 Finance 및 작업에 데이터를 삽입하는 방법도 알아봅니다. 

## 랩 설정

   - **예상 소요 시간:** 5분

## Instructions

지금까지 Finance and Operations 앱을 살펴보았으므로 이제 앱의 Excel 통합 시나리오를 살펴보겠습니다. 

1.  **재무 및 운영 홈** 페이지의 오른쪽 위에 있는 **USMF** 회사와 함께 작업하고 있는지 확인합니다. 

2.  **조달 및 소싱** > **설치** > **공급업체** > **공급업체 그룹**으로 이동합니다.

3.  작업 창에서 **Microsoft Office에서 열기** 를 선택하고 **Excel에서 열기에서** **공급업체 그룹(usmf)을** 선택합니다.

4.  **Excel에서 열기 창에서** **다운로드**를 선택합니다. 

5.  Excel 템플릿 파일이 다운로드되어 저장됩니다. 다운로드한 Excel 템플릿 파일을 **열고**, 필요한 경우 다른 표준 보안 프롬프트를 건너뛰거나 허용하고, 활성화를 닫고, **편집 사용을** 선택합니다. **이 추가 기능 신뢰를** 선택한 다음, 로그인합니다(요청이 있는 경우 동일한 자격 증명 사용). 

    로그인하면 데이터 커넥터 앱은 **공급업체 그룹** 테이블에서 기존 데이터를 새로 고치며 Excel 스프레드시트에 표시됩니다. 

6.  새 레코드를 만들려면 **공급업체 그룹** 필드, `Insurance vendor` **설명** 필드 및 `Net10` **결제 조건** 필드에 를 입력 `100` 합니다. 

7.  Microsoft Dynamics 데이터 커넥터 작업창에서 **게시** 단추를 선택합니다. 

8.  Dynamics 365 Finance 및 Operations에서 **공급업체 그룹** 목록을 새로 고쳐 새 레코드가 성공적으로 추가되었는지 확인합니다. 


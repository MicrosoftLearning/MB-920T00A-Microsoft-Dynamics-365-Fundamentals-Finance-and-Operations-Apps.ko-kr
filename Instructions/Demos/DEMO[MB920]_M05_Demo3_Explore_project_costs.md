---
demo:
  title: '데모 3: 프로젝트 비용 살펴보기'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>데모 3 - 프로젝트 비용 살펴보기

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. **Dynamics 365 for Finance and Operations**의 탐색 창에서 **모듈 > 프로젝트 관리 및 회계 > 작업표 > 내 작업표(모바일에 최적화)** 를 선택합니다.  
    이 데모 작성 시에는 모바일 디바이스를 사용하지 않았지만, **내 작업표(모바일에 최적화)** 옵션을 선택하면 모바일용 양식을 확인할 수 있습니다.

    ![내 작업표(모바일에 최적화)가 강조 표시된 프로젝트 관리 및 회계 메뉴의 스크린샷](./media/projops_costs_1_select_my_timesheets.png)  

    Microsoft 비즈니스 애플리케이션에서만 제공되는 차별화된 기능인 이 최적화 기능을 활용하는 경우 최소한의 학습만 진행하면 웹 버전과 모바일 버전을 모두 활용할 수 있습니다.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. **내 작업표** 페이지에서 **새로 만들기**를 선택합니다.  
    이제 구성된 설정을 기준으로 새 작업표를 만들겠습니다.

1. **새 작업표** 창에서 **날짜** 상자를 가리킵니다.  
    입력하는 날짜에 따라 작업표 기간이 결정됩니다.

1. **즐겨찾기에서 만들기**를 가리킵니다.  
    즐겨찾기를 저장해 두었다면 즐겨찾기에서 만들기를 선택하여 시간을 절약할 수 있습니다.

1. 완료되면 **확인**을 선택합니다.

1. **내 작업표 세부 정보** 페이지에서 **새로 만들기 +** 아이콘을 선택합니다.

1. **새 작업표 행** 창에서 **법인** 상자를 가리킵니다.  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. **프로젝트 ID** 메뉴를 선택합니다.

1. **Contoso Consulting** 프로젝트 등 사용 가능한 프로젝트 중 하나를 선택합니다.

1. 완료되면 **확인**을 선택합니다.  
    모바일에 최적화된 시간 입력용 화면이 열립니다. 그러면 각 프로젝트 날짜 및 범주(여기서는 **서비스**)의 시간 예약을 시작할 수 있습니다.

1. **시간 입력** 페이지의 **월** 상자에 **8**을 입력합니다.  
    이러한 방법으로 하루 동안의 작업 시간을 입력합니다.

    ![시간 입력 페이지의 스크린샷](./media/projops_costs_2_mon_box.png)

1. 이 데모에서는 Contoso Consulting 프로젝트 비용을 청구하는 데 사용할 시간 및 경비 항목을 만드는 과정을 단계별로 진행합니다.  
    모든 당사자가 로깅하는 시간의 특성을 파악할 수 있도록 프로젝트에 내부 및 외부 설명을 입력할 수도 있습니다.

1. 웹 및 모바일 표시용으로 최적화된 형식의 항목을 살펴본 후, 워크플로를 사용하여 승인 프로세스를 관리하는 방법을 알아봅니다.

1. 탐색 모음에서 **저장**을 선택합니다.

1. 왼쪽 탐색 메뉴의 **작업표** 아래에서 **내 작업표**를 선택합니다.

1. **내 작업표** 페이지에서 앞에서 만든 시간 항목을 선택합니다.

1. **작업표** 탭에서 범주 열을 가리킵니다.  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. **행 세부 정보** 아래에서 **내부 설명** 및 **외부 설명**을 가리킵니다.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. 탐색 모음에서 **워크플로** 탭을 선택합니다.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. **작업표 검토 워크플로** 창에서 **제출**을 선택합니다.

1. **작업표 검토 워크플로 - 제출** 창에서 설명을 더 추가합니다.

1. **제출**을 선택합니다.

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. **시간 거래** 페이지에서 페이지의 내용을 검토합니다.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

그런 다음에는 바우처 거래로 드릴다운할 수 있습니다.

1. 탐색 모음에서 **바우처**를 선택합니다.

1. **바우처 거래** 페이지에서 **원장 계정** 및 **계정 이름** 섹션을 가리킵니다.  
    이 섹션에서 총계정원장에 작업표가 반영되는 방식과 사용되는 계정을 확인할 수 있습니다.  

이제 동일한 Contoso Consulting 프로젝트용 경비 항목을 만들어 보겠습니다.

1. 탐색 창에서 **모듈 > 경비 관리 > 내 경비 > 경비 보고서**를 선택합니다.

1. **경비 관리** 페이지의 **보고서** 탭에서 **+ 새 경비 보고서**를 선택합니다.

1. 오른쪽 위의 회사 선택기에서 연결할 법인이 **USSI**인지 확인합니다.

1. **확인**을 선택합니다.

1. **경비** 페이지에서 **+ 새 경비**를 선택합니다.  
새 경비 행이 나타납니다.

1. **경비 범주** 열의 **범주 **드롭다운 메뉴에서 **연료**를 선택합니다.  
여기서 새 경비와 해당 세부 정보를 입력할 수 있습니다.

1. **거래 금액** 열에 **25.00**을 입력합니다.

1. **통화** 열에서 **USD**를 선택합니다.

1. 법인이 **USSI**가 아니면 USSI로 변경합니다.  
    세부 정보를 모두 입력했으므로 경비를 저장할 수 있습니다.

1. **저장**을 선택합니다.

1. 왼쪽 탐색 메뉴의 **작업 영역** 아래에서 **경비 관리**를 선택합니다.

1. **경비 관리** 페이지에서, 방금 만든 경비 보고서를 선택합니다.

1. **경비 보고서** 페이지에서 **프로젝트 ID** 상자를 선택하고 **00000093 Contoso Consulting**을 선택합니다.  

다음으로는 Consoto Consulting 프로젝트에 연료비를 청구할 것임을 지정하고 경비 관련 추가 정보를 입력할 수 있습니다.

1. **추가 정보** 상자를 가리킵니다.

1. 화면 오른쪽 아래에서 **저장 및 계속**을 선택합니다.

1. 화면 오른쪽에서 **제출**을 선택합니다.

1. **설명** 상자에 설명을 더 추가합니다.

1. **제출**을 선택합니다.

1. **경비 관리** 페이지에서 **승인 상태** 열을 가리킵니다.  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.

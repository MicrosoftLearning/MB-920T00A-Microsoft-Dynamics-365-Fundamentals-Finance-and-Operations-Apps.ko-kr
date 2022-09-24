---
demo:
  title: '데모 2: 송장 만들기'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>데모 2 - 송장 만들기

1.  **프로젝트 관리** 작업 영역으로 이동합니다.  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1.  **활성 프로젝트** 테이블의  **프로젝트 ID** 열에서 **00000093 Contoso Consulting**을 선택합니다.  

1. 그런 다음  **프로젝트 송장 제안** 페이지를 열어 Contoso Consulting을 대상으로 이전에 처리된 모든 송장을 확인합니다. 

1. 작업 창의  **청구** 탭에서  **프로젝트 송장 제안**을 선택합니다. 

1.  **프로젝트 송장 제안** 페이지의 탐색 모음에서  **새로 만들기**,  **송장 제안**을 차례로 선택합니다.  
    이 송장은 간단한 시간 및 재료 기반 프로젝트의 송장이므로 청구 규칙에서 송장 제안용 옵션을 선택할 필요는 없습니다. 

    ![새 송장 제안이 강조 표시된 프로젝트 송장 제안 페이지의 스크린샷](./media/projops_invoice_1_new_invoice_proposal.png)

1.  **송장 제안 만들기** 창에서  **거래 선택** 아래의 상자를 가리킵니다.  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![거래 선택 섹션이 강조 표시된 송장 제안 만들기 창의 스크린샷](./media/projops_invoice_2_select_transactions.png)

1.  **프로젝트** 드롭다운 메뉴에서  **00000093 Contoso Consulting**을 선택합니다. 

1. 이 예에서는  **송장 날짜**가  **2021/2/1**로,  **시작 날짜**가  **2021/2/1**로, 종료 날짜는 오늘 날짜로 설정되어 있는지 확인합니다.  
    매개 변수를 선택한 후 검색 단추를 선택하여 해당 매개 변수에 맞는 거래를 찾습니다.

1.  **검색**을 선택합니다.  
    이 데모에서는 Project Operations 내에서 단일 프로젝트의 송장 발행 프로세스를 진행합니다.

1.  **프로젝트 거래** 탭에서  **모두 선택**을 선택합니다.

1.  **확인**을 선택합니다. 

1.  **송장 제안** 페이지에서  **송장 품목 개수** 열을 가리킵니다.  
    여기서 송장 금액과 요약, 시간 거래 및 경비를 확인할 수 있습니다.

    ![송장 라인 금액 열이 강조 표시된 송장 제안 페이지의 스크린샷](./media/projops_invoice_3_invoice_line_amount_column.png)

1.  **시간** 탭을 가리킵니다. 

1.  **경비** 탭을 가리킵니다.  
    탭을 전환하여 경비 거래를 확인할 수도 있습니다.  
다음으로는 총계 단추를 사용해 비용 및 수익 측면에서 송장이 표시되는 방식을 살펴보겠습니다.

1. 탐색 모음에서  **총계**를 선택합니다.

1.  **총계** 페이지에서  **총계정원장** 열,  **고객** 열,  **품목 할인** 열을 가리킵니다.  
    총계 화면에서는 총계정원장, 신용 한도 등의 고객 정보, 할인, 매출세에 대한 송장의 영향과 송장 자체의 영향을 확인할 수 있습니다. 

1. 화면 오른쪽에서  **X**를 선택하여 페이지를 닫습니다.  
    대량 송장 발행을 수행할 수도 있지만 이 데모에서는 시간 및 재료 기반 프로젝트 하나의 송장을 발행하는 프로세스를 중점적으로 살펴봅니다. 

1.  **송장 제안** 페이지의 탐색 모음에서  **인쇄 미리 보기**를 선택합니다. 

1. 대화 상자에서  **인쇄 미리 보기**를 선택합니다.  
    여기서는 견적 송장의 인쇄 미리 보기 예를 확인할 수 있습니다. 

1. **X**를 선택하여 페이지를 닫습니다.  
    모든 정보의 유효성을 검사했으며 송장의 인쇄 미리 보기에서 문제가 없음을 확인했으므로 송장 제안을 게시할 수 있습니다.

1. 탐색 모음에서  **게시**를 선택합니다.

1.  **매개 변수** 탭을 선택합니다.

1.  **매개 변수**에서  **게시**를  **예**로 설정합니다.

1.  **인쇄 옵션**에서  **송장 인쇄**를  **예**로 설정합니다.

1.  **확인**을 선택합니다.

1.  **송장** 페이지에서  **송장** 번호를 가리킵니다.  
    송장 번호가 생성되었습니다.  
    송장을 게시하고 나면 송장 분개장에서 정보를 검토하고 원장 거래로 드릴다운할 수 있습니다.

1.  **프로젝트 관리** 작업 영역으로 이동합니다.

1.  **활성 프로젝트** 테이블에서 프로젝트  **00000093** **Contoso 컨설팅**을 선택합니다.

1. 작업 창의  **청구** 탭에서  **송장 분개장**을 선택합니다.

1.  **송장 분개장** 페이지의 작업 표시줄에서  **바우처**를 선택합니다.

1.  **바우처 거래** 페이지에서  **원장 계정** 열을 가리킵니다.  
    그리고 프로젝트 명세서 내에서 게시 결과 및 재무 인사이트도 확인합니다.

1.  **프로젝트 관리** 작업 영역으로 이동합니다. 

1.  **활성 프로젝트** 테이블에서  **00000093 Contoso Consulting 프로젝트**를 선택합니다.

1.  **Contoso Consulting** 페이지의 탐색 모음에서  **제어**를 선택합니다.  
    여기서 모든 프로젝트 세부 정보를 확인할 수 있습니다.  
    다음으로는 프로젝트 명세서에서 프로젝트 재무 정보를 확인해 보겠습니다.

1.  **프로젝트 명세서**를 선택합니다.

1.  **프로젝트 명세서** 페이지에서  **프로젝트 날짜** 섹션을 가리킵니다.  
원하는 날짜 범위에 대해 명세서를 만들 수 있습니다.

1.  **시작** 날짜 상자를 선택하고  **2021/2/1**을 입력합니다.
1. 
1.  **종료** 날짜 상자를 선택하고 오늘 날짜를 입력합니다.

1. 완료되면  **계산**을 선택합니다.

    ![계산 옵션이 강조 표시된 프로젝트 명세서 페이지의 스크린샷](./media/projops_invoice_4_calculate.png)

1.  **거래**를 가리킵니다.  
    먼저 프로젝트 송장 발행부터 시작해 보겠습니다.

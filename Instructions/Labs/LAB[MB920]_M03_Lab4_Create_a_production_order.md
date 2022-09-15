---
lab:
  title: '랩 4: 생산 주문 만들기'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>랩 4 - 생산 주문 만들기

## <a name="objectives"></a>목표

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

이 랩에서는 회사에서 생산할 품목에 해당하는 신규 생산 주문을 만들어야 합니다.

## <a name="lab-setup"></a>랩 설정

   - **예상 소요 시간:** 5분

## <a name="instructions"></a>Instructions

1. Finance and Operations 홈 페이지 오른쪽 위에서 작업을 수행할 회사가 USMF인지 확인합니다.

1. 필요한 경우 회사를 선택하고 메뉴에서 **USMF**를 선택합니다.

1. 왼쪽 탐색 창에서 **모듈** > **생산 제어** > **생산 주문** > **모든 생산 주문**을 선택합니다.

1. 상단 메뉴에서 **새 생산 주문**을 선택합니다.

1. **확인**의 **품목 번호** 상자에 **D0001**을 입력하고 확인된 품목을 선택합니다.

1. **생산**의 **배달 **상자에서 오늘부터 1개월 후의 날짜를 선택합니다.  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. **수량** 상자에 **20**을 입력합니다.

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![전체 생산 주문 만들기 창이 표시된 화면 이미지](./media/lp1-m4-new-production-order-pane.png)

1. **만들기**를 선택합니다.

---
lab:
  title: '랩 6: 생산 주문 만들기'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 222c557f935bc0dcfaa4f2e96049774f141ea028
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909730"
---
## <a name="lab-6---create-a-production-order"></a>랩 6 - 생산 주문 만들기

## <a name="objectives"></a>목표

생산 주문에는 생산할 제품과 수량, 계획된 완료 날짜 관련 정보가 포함됩니다. 그리고 품목 생산에 사용할 자재와 따를 프로세스 관련 정보도 포함됩니다.

이 랩에서는 회사에서 생산할 품목에 해당하는 신규 생산 주문을 만들어야 합니다.

## <a name="lab-setup"></a>랩 설정

   - **예상 소요 시간:** 5분

## <a name="instructions"></a>Instructions

1. Finance and Operations 홈 페이지 오른쪽 위에서 작업을 수행할 회사가 USMF인지 확인합니다.

1. 필요한 경우 회사를 선택하고 메뉴에서 **USMF** 를 선택합니다.

1. 왼쪽 탐색 창에서 **모듈** > **생산 제어** > **생산 주문** > **모든 생산 주문** 을 선택합니다.

1. 상단 메뉴에서 **새 생산 주문** 을 선택합니다.

1. **확인** 의 **품목 번호** 상자에 **D0001** 을 입력하고 확인된 품목을 선택합니다.

1. **생산** 의 **배달** 상자에서 오늘부터 1개월 후의 날짜를 선택합니다.  
    배달 날짜는 일정에 맞춰 품목을 배달하려면 생산 주문을 완료해야 하는 시기를 나타냅니다. 예약 프로세스에서 이 날짜를 사용할 수 있습니다. 예를 들어 배달 날짜 전의 특정 날짜에 주문을 예약할 수 있습니다.

1. **수량** 상자에 **20** 을 입력합니다.

1. **BOM/경로** 에서 BOM 번호 필드에는 현재 품목의 활성 BOM 번호가 자동으로 표시됩니다. 하지만 승인된 BOM 버전 목록에서 활성 BOM을 선택하여 생산 주문용 BOM을 변경할 수 있습니다. 경로 번호 필드에는 현재 품목의 활성 경로 번호가 자동으로 표시됩니다. 하지만 승인된 경로 버전 목록에서 활성 경로를 선택하여 생산 주문용 경로를 변경할 수 있습니다.

    ![전체 생산 주문 만들기 창이 표시된 화면 이미지](./media/lp1-m4-new-production-order-pane.png)

1. **만들기** 를 선택합니다.

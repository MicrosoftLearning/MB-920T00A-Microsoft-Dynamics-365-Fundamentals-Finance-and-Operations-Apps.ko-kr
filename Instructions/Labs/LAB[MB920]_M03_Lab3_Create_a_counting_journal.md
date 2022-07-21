---
lab:
  title: '랩 3: 계산 분개장 만들기'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e61646d33f284bb7e30b6f63a7db4778f58b47c
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116364"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>모듈 3: Microsoft Dynamics 365 Supply Chain Management의 기본 사항 파악

## <a name="lab-3---create-a-counting-journal"></a>랩 3 - 회계 분개장 만들기

1. Finance and Operations 홈페이지 오른쪽 위에서 작업을 수행할 회사가 **USMF** 인지 확인합니다. 필요한 경우 회사를 선택하고 드롭다운에서 **USMF** 를 선택합니다.

2. 왼쪽 탐색 창에서 **모듈** > **재고 관리** > **분개장 항목** > **항목 계산** > **계산** 을 선택합니다.

3. 작업 창에서 **+ 새로 만들기** 를 선택합니다. **재고 분개장 만들기** 대화 상자 양식이 **확인** 단추와 함께 아래쪽에 표시됩니다. **확인** 단추를 선택합니다.

4. 머리글 및 세부 정보와 함께 재고 계산 분개장 양식이 표시됩니다.

![머리글 및 세부 정보가 채워진 재고 계산 분개장 양식의 스크린샷](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. 작업 창에서 **줄 만들기 -&gt; 온라인** 을 선택합니다.

6. **보유량 계산 분개장 만들기** 대화 상자 창에서 **창고**, **재고 상태**, 위치 및 **번호판** 필드를 **예** 로 설정합니다. 

![설명된 대로 필드가 설정된 보유량 계산 분개장 만들기 대화 상자 창의 스크린샷](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. **레코드를 확장하여 섹션을 포함** 하고 **필터** 링크를 선택합니다. **항목 번호** 필드에서 **A0001** 을 선택한 다음 **확인** 을 선택합니다.

8. **보유량 계산 분개장 만들기** 대화 상자 양식의 맨 아래에서 **확인** 을 선택합니다.

항목 A0001의 보유 수량은 사이트, 창고, 위치 및 번호판이 분리된 **분개장 줄** 섹션에 표시됩니다.

9. **분개장 줄** 섹션의 **계산** 열에 각 사이트/창고/위치/번호판에서 계산된 숫자를 입력합니다. 다음 사항에 유의하세요.

    - **보유** 수량이 **계산** 수량과 같으면 **수량** 필드는 비어 있습니다.

    - **계산** 필드의 값이 **보유량** 필드보다 큰 경우 **수량** 필드에 양수 값이 포함됩니다.

    - **계산** 필드의 값이 **보유량** 필드보다 작은 경우 **수량** 필드에 음수 값이 포함됩니다.

10. 작업 창에서 **유효성 검사** 단추를 선택한 다음 **게시** 단추를 선택합니다.

11. 페이지를 닫고 홈페이지로 돌아옵니다.

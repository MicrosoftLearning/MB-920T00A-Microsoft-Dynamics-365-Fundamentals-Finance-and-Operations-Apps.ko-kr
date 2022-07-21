---
lab:
  title: '랩 2: Excel 통합'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116357"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>모듈 1: Dynamics 365 금융 및 운영 앱의 핵심 기능 살펴보기

## <a name="lab-2---excel-integration"></a>랩 2 - Excel 통합

지금까지 Finance and Operations 앱을 살펴보았으므로 이제 앱의 Excel 통합 시나리오를 살펴보겠습니다.

### <a name="task-1-create-template"></a>작업 #1: 템플릿 만들기

1. 재무 및 운영 홈페이지를 엽니다. 

2. **모듈** > **일반** > **일반** > **Office 통합** > **Excel 통합 문서** **디자이너** 로 이동합니다. 대부분의 탐색은 모듈을 통해 수행되므로 일반적으로 지정되지 않습니다.

3. 필터에서 **VendorGroup** 을 검색합니다.

4. 사용 가능한 필드 목록에서 **공급업체 그룹**, **설명** 및 **결제 약관** 필드를 선택한 후 오른쪽 화살표를 선택하여 선택한 필드 상자로 이동합니다.

5. 작업 창에서 **통합 문서 만들기** 단추를 선택합니다.

6. 오른쪽의 **다른 이름으로 저장** 패널에서 **다운로드** 단추를 선택합니다.

7. **다른 이름으로 저장** 을 선택하여 파일을 다운로드하고 **다운로드** 폴더에 저장합니다.

8. **일반** > **Office 통합** > **문서** **템플릿** 으로 이동합니다.

9. **새로 만들기** 를 선택합니다.

10. 오른쪽 패널의 **템플릿 업로드** 섹션에서 **찾아보기** 단추를 선택하고 이전에 다운로드한 파일을 선택합니다(기본 이름을 사용한 경우 DynamicsWorkbook임).

11. **템플릿 이름** 필드에 **CustomVendorGroup** 을 입력합니다.

12. **확인** 을 선택하고 **저장** 을 선택합니다.

### <a name="task-2-open-in-excel"></a>작업 #2: Excel에서 열기

1. **조달 및 소싱** > **설치** > **공급업체** > **공급업체 그룹** 으로 이동합니다.

2. **Microsoft Office에서 열기** > **Excel에서 열기** 를 선택하여 업로드한 새 템플릿인 CustomVendorGroup을 찾습니다.

3. **CustomVendorGroup** 을 선택하고 Excel 템플릿을 다운로드합니다.

4. 다운로드한 Excel 템플릿을 저장한 다음 열고, 필요한 경우 허용하고, 활성화를 닫고, **편집 사용** 을 선택합니다. 이 추가 기능을 신뢰한 다음 로그인합니다(요청된 경우 동일한 자격 증명 사용).

공급업체 그룹 테이블의 모든 기존 데이터가 Excel 스프레드시트에 표시됩니다.

5. 새 레코드를 입력합니다.

6. **공급업체 그룹** 필드에 **100** 을 입력하고, **설명** 필드에 **보험 공급업체** 를 입력하고, **결제 약관** 필드에 **Net10** 을 입력합니다.

7. Microsoft Dynamics Office 추가 기능 앱에서 **게시** 단추를 선택합니다.

8. **공급업체 그룹** 양식을 열어 새 레코드가 추가되었는지 확인합니다.


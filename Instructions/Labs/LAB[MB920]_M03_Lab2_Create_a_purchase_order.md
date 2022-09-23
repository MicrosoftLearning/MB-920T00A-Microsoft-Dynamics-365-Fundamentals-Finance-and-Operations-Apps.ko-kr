---
lab:
  title: '랩 2: 구매 주문 만들기'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>모듈 3: Microsoft Dynamics 365 Supply Chain Management의 기본 사항 파악

## <a name="lab-2---create-a-purchase-order"></a>랩 2 - 구매 주문 만들기

## <a name="objectives"></a>목표

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>랩 설정

   - **예상 소요 시간:** 10분

## <a name="instructions"></a>Instructions

1. Finance and Operations 홈 페이지 오른쪽 위에서 작업을 수행할 회사가 USMF인지 확인합니다.

1. 필요한 경우 회사를 선택하고 메뉴에서 **USMF**를 선택합니다.

1. 왼쪽 위에서 **탐색 창 확장** 햄버거 메뉴를 선택합니다.

1. **모듈** > **조달 및 소싱** > **구매 주문** > **모든 구매 주문**으로 이동합니다.

1. 모든 구매 주문 페이지의 상단 메뉴에서 **+ 새로 만들기**를 선택합니다.

1. 구매 주문 만들기 창에서 **공급업체 거래처** 메뉴를 선택하고 **US-101**을 선택합니다.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. **일반** 섹션을 확장합니다.

1. **보관 차원** 아래에서 **현장** 메뉴를 선택하고 현장 목록을 검토합니다.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. **날짜**에서는 배달 날짜 필드를 사용하여 조달한 상품과 서비스를 배달해야 하는 날짜를 지정합니다.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. 구매 주문은 보통 마스터 계획, 직접 배달 및 기타 프로세스를 완료하면 자동 작성됩니다.

1. **확인**을 선택합니다.

1. 수동 작성 시에는 대개 구매 담당자가 구매 주문을 작성합니다.

    ![머리글 메뉴의 위치가 표시된 화면 이미지](./media/lp1-m3-purchase-order-header-option.png)

1. **구매 주문 라인** 아래의 메뉴에서 **구매 주문 라인**을 선택합니다.

    ![구매 주문 라인 메뉴 옵션의 위치가 표시된 화면 이미지](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. **표시** 아래에서 **차원**을 선택합니다.

1. 이 랩에서는 USMF 회사의 구매 주문을 만들어 봅니다.

1. 차원 표시 창의 **제품 차원**에서 **색** 체크박스를 선택합니다.

1. 선택 사항: 설정 저장 토글 스위치를 선택하면 다음 번에 구매 주문 페이지를 열 때 선택한 차원도 주문 라인 표에 표시됩니다.

1. **확인**을 선택합니다.

1. **품목 번호** 셀 메뉴를 선택하고 **T0004**를 선택합니다.

1. 목록을 스크롤하는 대신 필터 상자에 번호를 입력해도 됩니다.

1. 품목 번호를 지정하여 제품과 서비스용 주문 라인을 만들 수도 있고, 조달 범주를 지정하여 경비로 주문 라인을 만들 수도 있습니다.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. **색** 메뉴를 선택하고 사용 가능한 옵션을 검토한 후에 색 중 하나 또는 여러 색 조합을 선택합니다.

1. 현장과 창고에는 대개 주문 머리글의 값이 입력됩니다. 하지만 일부 라인의 상품을 다른 위치로 배달해야 하는 경우에는 해당 필드를 재정의할 수 있습니다.

1. **수량** 상자에 **10**을 입력합니다.

1. 수량에는 제품의 최소 주문 수량(설정되어 있는 경우) 또는 값 1이 자동 입력됩니다.

1. 지정 가능한 몇 가지 추가 정보는 다음과 같습니다.

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. 페이지 아래쪽의 구매 주문 라인 아래에서 **라인 세부 정보**를 선택합니다.

1. **배달** 탭을 선택합니다.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. 구매 주문 라인 페이지를 닫습니다.

1. 모든 구매 주문 페이지에서 필터 기능을 사용하여 새 구매 주문을 찾습니다.

1. 새 구매 주문을 찾은 후 모든 구매 주문 페이지를 닫고 홈 페이지로 돌아옵니다.

# 91App-Analysis
### 91APP Description
[91APP](https://www.91app.com/?lang=MY) is a leading omnichannel commerce solutions provider in Asia that provide a seamless multi-channel shopping experience for consumers. 

### Dataset Description
The datasets come from a apperal store which owns both online and offline store.
There a three different datasets.
1. **MemberData**
  - size: 12MB
  - shape: 159,835 rows x 11 columns
  - time range: All member data
2. **OrderData**
  - size: 54MB
  - shape: 508,083 rows x 18 columns
  - time range: 2016/01/01 - 2019/04/04
3. **OrderSlaveData**
  - size: 130MB
  - shape: 1,159835 rows x 20 columns
  - time range: 2016/01/01 - 2019/04/30
4. **BehaviorData**
  - size: 2.7GB
  - shape: 22,061,563 rows x 15 columns
  - time range: 2018/03/05 - 2019/04/30

### Column Description
|Column Name|Definition|Values|
|-----------|----------|------|
|UUID       |Unique User Id|String|
|TransactionNum|The unique number of transaction|String|
|TradesDate|The date when the transaction happened|yyyy-mm-dd|
|ChannelType|The big channel of order|OfficicalEcom, Pos, Mall(The old version of Ecom)|
|ChannelDetail|The detail channel of purchase|DesktopOfficialWeb, MobileWeb, iOSApp, AndroidApp, 其他(others)|
|PaymentType|The way the customer pays|Cash, Family, SevenEleven, CreditCardOnce, LinePay, ATM|
|ShippingType|The shipping way|Store, Family, SevenEleven, Home, LocationPickup, SevenElevenPickup, FamilyPickup|
|TsCount|The amount of category of the order|Int|
|Qty|Product amount of the order|Int|
|TotalSalesAmount|The amount the person actually paid for the order|Int|
|TotalPrice|The amount the person should paid|Int|
|TotalDiscount|The discount of the order|Int|
|TotalPromotionDiscount|The promotion discount of the order|Int|
|TotalLoyaltyDiscount|The discount of membership|Int|
|Status|The status of the order|Finish, Return, Cancel, Overdue, New, Fail, Shipping|

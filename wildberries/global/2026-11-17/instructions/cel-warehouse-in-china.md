# CEL仓库

Source: https://seller.wildberries.ru/instructions/ch/ch/material/cel-warehouse-in-china
Retrieved: 2026-11-17

更新日期 11/16/2026

仓库 CEL Hunchun

在 [WB Plus](https://seller.wildberries.ru/instructions/ch/ch/material/wb-plus-model-in-china?categoryId=about-marketplace-model-fbs-china&goBackOption=prevRoute) 销售模式下，您可以将商品存储在WB Plus合作仓库——CEL Hunchun 仓库中。此举将有助于加快您商品的配送速度，并因此提升其在搜索结果中的排名。

CEL Hunchun 合作仓库的优势:

- 配送至中部地区，最快可在10天内送达（含带电池商品）
- 90天免费仓储
- 所有服务免费：涵盖商品入库、卸货、分拣、上架等所有环节。
- 免费提供国际运输标签，有效减少您的人工成本投入。
- 免费报关与清关服务：全流程报关服务，无需承担额外报关费用

## 如何设置WB Plus CEL Hunchun仓库

步骤1

如需接入 WB Plus CEL Hunchun仓库，请联系承运商并提交接入申请。

联系方式：

联系人：文迪

电话：15307627132

微信 ID：Wendihhhcel（15307627132）

[邮箱：huangwendi@szcel.com.cn](mailto:%E9%82%AE%E7%AE%B1%EF%BC%9Ahuangwendi@szcel.com.cn)

步骤2

申请处理完成后，该仓库将在您的个人账户中显示为可用

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/fe1d6208-281a-41c3-b388-494e4d49a772.png.webp)

步骤3

在个人账户中选择仓库“50072222-Hunchun-WB Plus 7Days-truck+air-All goods”

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/2ae4743b-f67f-460a-b5e9-10c5f3f155a7.png.webp)

步骤4

提供CEL令牌（token）和仓库编号（warehouse id）

当您为与 Wildberries 的集成配置 API 时，会创建 API 令牌。您可以在“ [API 集成](https://seller.wildberries.cn/api-integrations)”部分查看该令牌。

要获取令牌，请点击“创建新令牌” → 输入任意令牌名称并选择“内容 \+ FBS” → 令牌将被创建。

使用它为您的店铺在 OMS CEL 系统中授权。为此，请将其粘贴到“token”字段中。

请注意，在创建 API 令牌时，不需要勾选“测试”和“只读”字段。如果您在创建令牌后没有立即复制，请将其删除并创建新的令牌。

在您使用令牌于 OMS CEL 系统期间，不能在 WB卖家后台的个人账户中删除它。如果您删除令牌，系统将无法获取 Wildberries 的订单、标签和供货数据。

Warehouse id 可在卖家后台的“供货与订单”板块中，“我的仓库与通行证”部分查看。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/ddff2211-9783-43a1-813b-7d3d4e0d270b.png.webp)

步骤5

在OMS CEL中进行仓库设置- 珲春非保税仓。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/169ed291-1919-40a1-bfbc-301ba9439fe5.webp)

步骤5.1 — 登录Wildberries平台，创建授权API，获取token.

获取token的路径：卖家中心 → API访问权限 → 创建新令牌 → 填写令牌名称（可以自定义）→ 选【内容+市场】→ 创建令牌 → 创建成功，复制令牌（该令牌会用于OMS授权WB店铺，填写在OMS-WB授权的token项中）

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/befc52dd-f3ad-4441-b0f5-333d05ab17ed.png.webp)

注意: 创建API授权时，不要勾选【测试】，不要勾选【它刚刚阅读】

如果授权创建完毕未及时复制出令牌，可以删除旧授权，新建一个授权，使用新token到OMS授权。

店铺API token在OMS使用期间，店铺后台不能删除这个令牌，否则OMS将无法获取与该WB店铺发货相关的的订单/面单/批次交货单等线上平台数据。

步骤5.2 — OMS系统

登录OMS系统，到【平台账号管理】界面，进入wildberries平台账号授权。菜单：OMS-平台管理-平台账号管理 选择Wildberries，填写店铺名和token，点击【确认】

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/8e17c400-2550-404d-9ce0-e472578e41ad.png.webp)

步骤5.3 — 平台账号开启拉单

菜单：OMS-平台管理-平台账号管理

【平台账号管理】界面，可查看到授权成功的新店铺账号

点击【开启拉单】，系统开始自动抓取新账号的已支付未发货订单.

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/6c4096f6-156f-4b83-a166-9875daae0920.png.webp)

如果有授权时间之前的订单要抓取到OMS系统仓库发货，可点击【抓取订单】，可以选择时间段抓取订单。

如果需要抓取指定的订单，可选择时间+指定单号，对指定订单进行拉取

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/d040829a-7bea-4639-9000-14a427d38814.webp)

如果没有正常抓取，可能是授权信息错误，可点击【修改】重新授权。

店铺授权异常，如何处理?

一般是token填写错误，例如token前后多填了空格. 处理方式：指定店铺重新授权. 平台账号管理界面，找到订单对应的店铺. 点击【修改】注意：店铺重新授权不要修改店铺名称，填写正确的token后直接点【确认】。

步骤5.4 — 维护平台SKU关系

OMS系统下载到的平台订单商品明细为平台SKU\*数量，其中平台SKU需要转换为仓库SKU，仓库才能正常发货，平台SKU与仓库SKU的对应关系，需要在OMS系统维护.

菜单：OMS-平台管理-平台SKU关系

步骤5.4.1 — 手工添加平台SKU关系，

点击【新增】，填写平台SKU，选择账号，维护该账号下 平台SKU实际要发货的OMS SKU和数量（单品一对一发货实际发1个，数量填1）。如果发多品，可点击+，添加OMS SKU2。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/ceaccfb0-4c5e-41c0-b8a8-306be5bbcfab.png.webp)

例如在diy-fun-toys账号下的订单，客户购买1个平台SKU：1123-78，实际仓库需要发的SKU为：1个SKT-1123-8+1个SKT-1123-7，数据维护如下图：

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/3c1bf981-328c-4cfd-ab96-48b4d10225df.png.webp)

步骤5.4.2 — 批量导入平台SKU关系

点击【导入】，下载系统模板，填写信息后批量上传

只绑定平台，未指定店铺，表示该平台下按照对应行的SKU关系发货.

绑定平台+指定店铺，表示在该店铺下按照对应行的SKU关系发货. 未指定平台+未指定店铺时，对应行的SKU关系适用于所有订单.

系统优先识别指定店铺的SKU关系；无指定店铺SKU关系，有指定平台时，使用指定平台对应的SKU关系发货；未指定店铺且未指定平台时，作为通用SKU关系发货。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/9dc325f0-0006-4be0-b212-134fdc479e87.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/2a1c4688-174d-400a-94ff-f1da077971da.png.webp)

步骤5.5 —【待处理】的平台订单，转系统订单并审核

系统自动下载的平台订单，需要在平台订单管理界面查看后处理，才能转为仓库订单发货

菜单：OMS-平台管理-平台订单管理

选择要发货的平台wildberries，【待处理】状态下，勾选需要仓库发货的订单.

- 点击【转系统订单并审核】，该订单将生成一个对应的系统订单，并自动审核该订单，审核结果在【出库订单】-【订单列表】查看，审核成功的订单可在【已审核】状态下查看，审核失败的订单可在其他状态查看. 已处理状态下，也可以看到对应的系统订单状态

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/213b5bd1-8bb9-452f-888a-fa4c790a3490.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/b2e21015-1b56-4906-8e9e-ce01d1d917de.png.webp)

- 点击【转系统订单待审核】，该订单将生成一个对应的待审核系统订单，可在【出库订单】-【订单列表】-【待审核】状态查看，注意：待审核状态的订单，需要审核成功，才会被提交至仓库操作发货.
- 暂时无需发货的订单，可勾选订单，点击【冻结】，平台订单将转到【冻结】状态，该状态订单也可转系统订单继续处理

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/9f19e487-e2af-499a-8ddf-1fd2b7917a52.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/faa94d35-bc40-4ab9-bfe0-3a3e5b4a1875.png.webp)

- 订单信息不使用/不再发货可点击【作废】。注意，点作废只针对本次拉取的订单内容，不会对应作废平台上的订单。OMS系统作废的平台订单，会显示在OMS【平台订单黑名单】界面，如果需要恢复发货，可以将平台订单从黑名单界面作废.
- 【重新匹配SKU】：适用于平台订单已抓取到OMS系统之后，又修改了平台SKU关系，或者平台抓取订单后才维护平台SKU关系的情况。点击可再次为平台订单匹配海外仓SKU。
- 【映射同名SKU】：该功能是系统快速创建平台SKU关系。适用于平台SKU=客户SKU或仓库SKU。 例如A客户的平台SKU为A1，系统SKU=A-A1，映射同名SKU时，系统自动创建平台sku 的A1=系统A-A1

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/2b16e15c-bb41-4c50-a9da-5bf2e830087a.png.webp)

- 如果转系统订单时提示\[未匹配到SKU对应关系:XXXXXX\]，表示所选择的平台订单SKU，未维护对应的系统发货SKU。 可点击【新增SKU映射】或者到【平台SKU关系】界面，补充维护该平台SKU对应的系统SKU关系

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/bc41b9cf-181e-4d11-8fe1-88b6e7598c1d.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/9055f862-4f13-49f0-84e6-7edcc9104522.webp)

步骤5.6 —【已处理】的平台订单，回传单号，创建WB发挥批次（适用于wildberries FBS订单）

平台单转为系统订单后，FBS订单使用平台面单发货（wildberries FBS），【已处理】的平台订单需要在OMS操作回传单号，用于海外仓获取平台订单的跟踪号和发货面单。

操作步骤：平台选择wildberries，【已处理】状态下，勾选【已审核】的订单，点击【回传单号】。

因WB店铺回传单号要向平台创建发货批次，批次按店铺生成，查询条件中可以先选择一个WB店铺，对该店铺当日订单回传单号。

注意：这一步，WB订单要单个店铺操作，无法对不同店铺的订单创建一个发货批次。

操作【回传单号】后，要及时关注回传结果。回传异常的订单，可以在【已处理】订单下看到异常提示。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/46021431-5f37-4b79-8754-779df0d6e7a2.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/f2806f94-b10b-408f-9e04-d0ea76ff86bd.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/5ee87892-e85b-49b5-84aa-e77aefc08980.png.webp)

步骤5.7 — 当日WB店铺待发货订单处理完毕，提交发货批次到平台

界面：OMS-平台管理-平台发货批次

选择WB发货批次，点击【提交发货】

批次提交发货后，可以下载交货单，给仓库打印批次箱唛二维码用于站点交货。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/69e3abf2-2be1-4bd4-96a2-9c130b8aa4f7.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/48c58201-18c0-4cc9-8bd3-f06eed751db4.png.webp)

步骤6

将实际库存中的商品上传至平台

如有任何疑问，欢迎联系 CEL 相关业务负责人。

## 常见问题

费用是多少？

费用为 48 RMB/kg + 9 RMB/件。

如何在系统中显示发货？

目前在 WB 卖家后台暂时无法显示发货信息。您只需在 OMS CEL 中操作发货，Wildberries 平台上无需额外操作

API 令牌在哪里可以找到？

在为 Wildberries 设置 API 集成时，您需要创建 API 令牌，可在“API 集成”栏目中查看。

获取令牌的步骤：点击“创建新令牌”→ 输入任意 Token 名称并选择“内容 + FBS”→ 系统将生成令牌。

将该令牌填入 OMS CEL 系统的 “token” 字段即可完成店铺授权。

注意事项：创建 API 令牌时，不要勾选“测试”和“只读”；如果在创建后未及时复制 令牌，请删除并重新创建；

在 OMS CEL 系统使用令牌期间，不要在 WB卖家后台删除该令牌，否则系统将无法获取 Wildberries 的订单、标签和供货信息。

哪里可以查看商品库存？

目前 WB 卖家后台暂不支持查看送至合作仓库的库存，您只能在 CEL 订单管理系统中查看库存情况。

如何将 Wildberries 添加到 OMS CEL 系统？

首先在“API 集成”栏目中创建 API 令牌（点击“创建新令牌”→ 输入令牌名称 → 选择“内容 + FBS”→ 生成令牌）。

然后登录 OMS CEL 系统，进入“平台账户管理”，选择 Wildberries，填写店铺名称与 API 令牌并点击“确认”完成授权。

最后点击“开始下载”，系统会自动获取已付款但未发货的订单。

如何导入授权前已创建的订单？

点击“下载订单”，选择时间范围即可批量导入授权前的订单；如需导入指定订单，可选择日期、时间并输入订单号。

若订单无法导入，请检查令牌是否正确，必要时点击“修改”更新令牌。

授权 Wildberries 店铺到 OMS CEL 系统时出现错误怎么办？

这类错误通常是令牌输入不正确造成的，例如多输入了空格。

请重新授权店铺：点击“修改”，输入正确的令牌并点击“确认”，无需更改店铺名称。

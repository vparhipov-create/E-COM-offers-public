# CEL Chengdu 仓库

Source: https://seller.wildberries.ru/instructions/ch/ch/material/cel-warehouse-in-china-chengdu
Retrieved: 2026-11-23

更新日期 11/17/2026

CEL Chengdu 仓库

在 [WB Plus](https://seller.wildberries.ru/instructions/ch/ch/material/wb-plus-model-in-china?categoryId=about-marketplace-model-fbs-china&goBackOption=prevRoute) 销售模式下，您可以将商品存储在WB Plus Chengdu合作仓库——CEL仓库中。此举将有助于加快您商品的配送速度，并因此提升其在搜索结果中的排名。

CEL Chengdu 合作仓库的优势:

- 配送至中部地区，最快可在10天内送达（含带电池商品）
- 90天免费仓储
- 所有服务免费：涵盖商品入库、卸货、分拣、上架等所有环节。
- 免费提供国际运输标签，有效减少您的人工成本投入。
- 免费报关与清关服务：全流程报关服务，无需承担额外报关费用

接下来，指南将分步说明如何设置 WB Plus CEL Chengdu 仓库。

## 步骤 1

如需接入 WB Plus CEL Chengdu仓库，请联系承运商并提交接入申请。

质量与投诉：何伟成

联系方式：17817010732

微信ID：ACEHO-623

邮箱： [heweicheng@szcel.com.cn](mailto:heweicheng@szcel.com.cn)

售前咨询：CEL市场部

联系方式：15710826448

微信ID：wxid\_bpgvu8roweno12

[邮箱：heweicheng1@szcel.com.cn](mailto:%E9%82%AE%E7%AE%B1%EF%BC%9Aheweicheng1@szcel.com.cn)

客服咨询：CEL客服中心

联系方式：15323417804

微信ID：kentkandy

[邮箱：zhousen1@szcel.com.cn](mailto:%E9%82%AE%E7%AE%B1%EF%BC%9Azhousen1@szcel.com.cn)

## 步骤2

申请处理完成后，该仓库将在您的个人账户中显示为可用

50239292-WB Plus Chengdu-8Days-Air-All goods

## 步骤3

在个人账户中选择仓库“50239292-WB Plus Chengdu-8Days-Air-All goods”

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/1dfbcb09-c6d5-4a46-bcde-fe065c1a83eb.png.webp)

## 步骤4

提供CEL令牌（token）和仓库编号（warehouse id）

当您为与 Wildberries 的集成配置 API 时，会创建 API 令牌。您可以在“ [API 集成](https://seller.wildberries.cn/api-integrations)”部分查看该令牌。

要获取令牌，请点击“创建新令牌”→ 输入任意令牌名称并选择“内容 \+ FBS” → 令牌将被创建。

使用它为您的店铺在 OMS CEL 系统中授权。为此，请将其粘贴到“token”字段中。

请注意，在创建 API 令牌时，不需要勾选“测试”和“只读”字段。如果您在创建令牌后没有立即复制，请将其删除并创建新的令牌。

在您使用令牌于 OMS CEL 系统期间，不能在 WB卖家后台的个人账户中删除它。如果您删除令牌，系统将无法获取 Wildberries 的订单、标签和供货数据。

Warehouse id 可在卖家后台的“供货与订单”板块中，“我的仓库与通行证”部分查看。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/a461dea1-3bf8-408a-8568-a6850020deb2.webp)

## 步骤5

本指南帮助您使用 CEL 成都仓（WB Plus）从系统注册、备货入库到平台发货的完整操作。请按章节顺序阅读，并对照实际操作界面逐步完成。

| 项目 | 内容 |
| --- | --- |
| 产品名称 | Chengdu WBPlus-50239292-WB Plus Chengdu-8Days-Air-All goods |
| 承诺时效 | ≤ 8 天 |
| 价格 | 48 元/公斤 + 30 元/票 |
| 尺寸限制 | 三边之和不超过 200 厘米，单边不超过 115 厘米 |

入库要求

| 要求项 | 说明 |
| --- | --- |
| 起备数量 | 总件数 60 件起备，每种 SKU 20 件起 |
| 密度要求 | 单个 SKU 的密度重要高于 120KG/每立方米（低于 120密度的无法入库） |

操作流程总览

完成一次成都仓备货并正常发货，需依次完成以下环节：

1. CEL 系统注册与店铺绑定；
2. WB 平台授权（创建 API 令牌并绑定 OMS）；
3. OMS 产品 SKU 维护（创建产品）；
4. 备货入库（创建入库单、打印标识、发货到仓）；
5. 渠道开通（货物上架成功后）；
6. 平台添加仓库；
7. 平台 SKU 关系映射；
8.  出单后 WMS 系统预报发货。

### 第一步：CEL 系统注册与店铺绑定

注册账号

1.  打开 CEL 系统网址： [http://82.157.40.136:8010](http://82.157.40.136:8010/)
2. unknown
进入网址后，点击左下角注册按钮，填写注册信息。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/f143fe45-e650-451a-84ce-403e7a5dd194.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/7314fe74-3be9-4cc2-8cbe-5d4a2dfc9483.png.webp)

填写注册信息并审核

填写完必要信息后，选择成都仓，系统自动审核后账号方可使用。

用户中心设置（子账号与角色）

子账号管理：根据需求可创建子账号。将创建的子账号与已创建的角色绑定后，子账号即创建完成，并拥有该角色的功能权限。

角色管理：主账号可进行子账号分配。先创建子账号的角色，为每个角色赋予不同的功能权限，再将子账号绑定到对应角色。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/6fc45a5c-c23b-4ce4-90e0-6278a93fc2d4.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/1e0c53cc-a7df-4d67-ac3f-dc47b00d6a0b.png.webp)

### 第二步：WB 平台授权

在 Wildberries 平台创建 API 令牌（获取 Token）

1. 登录 Wildberries 平台，进入右上角卖家中心；
2. 进入API 接口对接，点击创建令牌；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/920e83a0-3824-467d-ad00-280551ea5125.png.webp)

3\. 填写令牌名称，授权范围选择：内容、FBS、统计、价格与折扣、供应；

4\. 点击创建令牌，完成后复制该 Token，用于后续 OMS 授权。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/b48db1f2-e2b2-41fd-92af-f8d54d2a88ba.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/13be7efa-cc5a-402d-b51d-58b6f63b46a2.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/cf061a64-daf9-4092-84f6-3e88874f96ec.png.webp)

在 OMS 系统绑定 WB 店铺

1. 登录 OMS 系统，进入平台管理-平台账号管理；
2. 点击更多选项，选择 WB 平台；
3. 点击添加 WILDBERRIES 授权：第一步点击"前往获取授权码"；第二步填写店铺昵称和授权码；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/e32d57e0-fcc8-46a0-995a-4985d65c1b0f.png.webp)

4\. 店铺简称：填写系统中店铺的名称；Token：填写 WB 平台店铺获取的 Token；

5\. 填写完成后点击确定，完成绑定。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/1e95dffa-33e3-4e7b-ba99-07eb6c12b521.png.webp)

系统不会自动抓取在 OMS 授权店铺之前平台产生的订单。如需抓取历史订单，请使用【抓取订单】功能，选择指定时间段手工抓取

开启拉单与设置抓单仓库:

- 绑定成功后，店铺会显示在【平台账号开启拉单】界面。选定要抓取的订单，选择订单产生的日期，即可将平台订单抓取到系统中；
- 建议拉取后设置自动抓取订单；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/fe8ad09e-6f6e-4acb-ae9e-be74a73dbc56.png.webp)

- 设置抓单仓库：绑定成功后，可选择只显示成都仓，并只抓取该仓库的订单。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/89fbe9db-f251-4d75-b2fd-bca57a764d44.png.webp)

### 第三步：OMS 产品 SKU 维护

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/1490a46e-8b30-4dc1-a066-7102ee901de7.png.webp)

创建 SKU（产品）

1. 路径：基础资料-产品列表；
2. 在备货发货前，需在系统中创建自己的产品（可自定义），支持单个新增或批量导入；
3. 创建产品后需审核，审核通过后产品才会生效（带星号的字段都需填写）；
4. 创建完成后，检查产品的状态为"可用"即可。

产品条码说明：产品条码 = 单品条码。如果货品上已贴有条码，请将该条码录入WMS。

如平台店铺已有商品，可提前将 SKU 映射关系维护到系统中，方便日后订单操作；也可备货完成后再操作

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/57588629-0c9e-4822-bff5-b6eb9763a6fb.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/981fdf35-39a8-423c-8645-408d2cb795d5.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/0d6c2f26-050f-4017-938f-38b367e86651.png.webp)

### 第四步：备货入库

基本流程

1. 建立自发入库单（状态：新建）；
2. 入库单确认发货（状态：在途）；
3. 打印各类单据、箱唛、条码；
4. 仓库收货（状态：收货中）；
5. 仓库收货完毕（状态：收货完成）；
6. 仓库上架完毕（状态：上架完成），即为备货完成。

确认入库方式

- 卖家需自行区分保税和非保税备货模式，选择对应目的仓库；保税备货需选择对应的附加服务（保税备货必选）；
- 自发入库：即自行将货物发往目的仓库，入库方式选择"自发入库"；
-  选择【目的仓库】，填写单据号【参考单号】，参考编号不用填。

创建入库单

1.

unknown

维护创建完产品后，进入【创建入库单】；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/cba1edcb-4651-4968-a3da-1b73026d42e9.png.webp)

2\. 先选择入库方式、目的仓库等重要选项，再添加本单要备货的商品；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/4da97a45-66ed-4c44-8555-85b286233069.png.webp)

3\.

unknown

填写箱号以及备货数量，提交后入库单即创建完成；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/557db8fd-1819-49fe-aa01-c73fa8be0615.png.webp)

4\. 创建完成的入库单（新建状态）会多出几个功能选项，点击确认发货后，入库单状态变为"在途"，仓库端将显示；

5\.

unknown

实货到达仓库、仓库操作上架后，状态变为"上架成功"即为备货完成（可通过入库单状态判断仓库操作进展）。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/94e99704-c9ee-4c1d-9a04-4f626796a062.png.webp)

不要选择"中转入仓"。选择"自发入仓"同样可以通过营业部中转，运费：4 元/kg。同箱混装需做好物理隔离。

### 打印入库标识

标识用途：

- 入库清单：放于头箱（编号为 1 的箱）内；
- 箱子箱唛：与实际箱号对应，贴于每个箱子上；
- 产品条码：贴在每一个 SKU 的单品外包装上。

打印方式：

- 方式一（入库单管理）：选中"在途"状态，可在此界面打印入库单及 SKU 标签；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/b7914102-ff22-4c77-b890-be0b7df295c9.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/9dcf752a-7f98-4e88-ac9d-27e29276460b.png.webp)

- 方式二（生成入库标识）：CEL 系统【生成入库标识】→ 打印箱唛。

打印入库标识后请先扫描，确认扫描正常再交货

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/5c5346e5-bf96-4c52-82d2-3dc4416a88fd.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/eb89d43e-2cc5-49b6-893d-265676bc4237.png.webp)

成都仓收货确认

如到货有数量差异，客服人员通知贵司后，请在系统【入库单管理】界面查看收货数量（收货中），确认差异数量后，点击【收货完成】完结此次未收数量。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/972d79ae-20f2-49f0-a6c6-d9c80726706f.png.webp)

### 第五步：发货至成都仓（收货地址）

备货完成后，请将货物发往以下地址：

| 项目 | 内容 |
| --- | --- |
| 收货地址 | 地址：成都天府国际空港综合保税区凌穹北路2111号1号仓库 |
| 联系方式 | 收货人：刘麟涛  电话号：13331661272 |

### 第六步：渠道开通（货物上架成功后）

在 CEL 系统备货完成、成都仓库收到包裹后，请提供店铺 ID 给对接您的 CEL 客服，客服将针对性地为您打开 Chengdu WB Plus - 50239292-WB Plus Chengdu-8Days-Air-All goods仓库渠道。

店铺 ID 获取位置：平台账户信息处。如 ID 不显示，小技巧：切换一下语言即可显示。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/1da8a738-26a0-4ae5-abd0-20683b07e44d.png.webp)

### 第七步：平台添加仓库

请提前提供卖家 ID 给 CEL 商务打开仓库后，按以下路径操作：我的仓库与通行证 → 创建仓库 → 新卖家仓库 → 选择接送点 → 添加 CEL 仓库。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/93491e88-d230-44c7-b0f0-c345fede61d9.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/7ebde244-0007-4c9c-8983-fd4a2e9e061f.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/4e46c7eb-e429-44fd-a77d-eefd08fa0356.png.webp)

我的仓库与通行证

进入 WB partners → 我的仓 → 卖家库存 → 我的仓库与通行证。

创建仓库

在我的仓库和通行证页面，点击【创建仓库】完成仓库创建。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/37138891-63d8-4990-b19e-34341e2fa0bf.png.webp)

添加 CEL 仓库

1. 在计划发货仓输入：50239292，搜索后选择"50239292-WB Plus Chengdu-8Days-Air-All goods即可；
2. 仓库类型选择"全部"（KT+ / SGT）；
3. unknown
确认仓库信息后点击【添加完成】。

### 第八步：平台 SKU 关系映射

OMS 系统拉取到的平台订单商品明细为"平台 SKU × 数量"，其中平台 SKU 需转换为仓库 SKU，仓库才能正常发货。平台 SKU 与仓库 SKU 的对应关系需在 OMS 系统中维护。

菜单路径：WMS-平台管理-平台 SKU 关系。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/cee2ff28-0aac-45dd-b4c8-df64f5a07c09.png.webp)

手工添加平台 SKU 关系

1. 点击【新增】，填写平台 SKU，选择账号；
2. 维护该账号下平台 SKU 实际要发货的 OMS SKU 和数量（单品一对一发货实际发 1 个，数量填 1）；
3. 如发多品，可点击"+"添加 SKU；
4. 确认无误后点击确定。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/be8077ee-cbcf-4c6d-96ee-c66e2698b609.png.webp)

批量导入平台 SKU 关系

1. unknown
点击【导入】，下载系统模板；
2. 按模板填写信息后批量上传。

平台条形码可以为空；有多个 SKU 时填写在蓝色框内信息即可。平台 SKU 可在平台商品详情页获取。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/4f6cf6f5-3a54-4cb2-80d5-0f9f80abe9ac.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/17fb631f-85e2-4047-8598-3d2fbc6025e1.png.webp)

### 第九步：出单后 WMS 系统预报发货

1. 平台出单后，将平台订单转化为系统订单：平台订单管理 → 选择 WB → 勾选要发货的订单 → 转系统订单并审核（注意先选平台才会出现对应的操作选项）；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/0cc9c5a4-c401-446e-bea2-212ec0657e86.png.webp)

2\. 此时订单会从"待处理"状态变为"已处理"状态；

3\. 选定订单，点击回传单号，创建发货批次（批次名称可自定义）；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/e4337405-f159-4f24-bb25-de65e3e11152.png.webp)

4\. 选择仓库和运输方式：仓库选择"成都非保税仓"，运输方式选择 FBS；

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/686aed29-2033-45be-9c5d-b7efc18e402f.png.webp)

5\. 回传单号创建的批次，可在对应界面找到，此时批次状态为"新建"，点击提交发货后批次状态变为"完成"，平台店铺中订单的状态也将随之改变。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/e5392e82-021a-4cd9-8b39-2feb7a590329.png.webp)

智能手机卖家：IMEI 码回传

金额在 20000 卢布以上的手机卖家，平台要求卖家填写 IMEI 码。

卖家需要贴 IMEI 码，请务必将 IMEI 码贴在打包好的外包装上！仓库会根据贴好的 IMEI 码直接传输给平台。回传完成后，平台后台订单的 IMEI 状态会显示 ✅。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/f0e029f7-cf1f-46e5-a35b-36c9f43481ec.png.webp)

售后处理规则

| 场景 | 处理规则 |
| --- | --- |
| 在仓未发出的被取消订单 | 还货上架 |
| 在途被取消订单 | - 清关之前和清关失败的订单：等待 CEL 客服通知卖家给出订单处理决策；<br>- 清关成功后取消的订单：由 WB 平台处理 |
| 无人认领 / 买家拒收订单 / 退货 | 由 WB 平台处理，卖家可联系平台客服 |
| 查询物流轨迹 | 登录 [http://tms.celdt.cn/track\_query.aspx](http://tms.celdt.cn/track_query.aspx) 查询 |

仓内操作费仓内增值服务及打包材料价格表

仓内操作费用增值服务及打包材料的具体费用，请向对接您的 [CEL 客服索取](http://cms.celdt.cn:8383/user?bid=035c72a1076d2249555a836dea20c774&groupid=0%20)。

联系与支持

- 账号注册审核、渠道开通、订单处理决策等事项，请联系 [对接您的专属 CEL 客服](http://cms.celdt.cn:8383/user?bid=035c72a1076d2249555a836dea20c774&groupid=0%20)；
- 物流轨迹查询： [http://tms.celdt.cn/track\_query.aspx](http://tms.celdt.cn/track_query.aspx)

常见问题

Q1：再添加仓库时，提示"不分《我的仓库与通行证》已被禁用"如图

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/d6f29204-72db-41f5-b961-9b12c3517be2.png.webp)

A1：选择中国直发退货：

- 左边（用于退货自提点5个）：如果卖方只从中国出售，可以随机选择5个地址即可。
- 右边（境外）：需要单击（右键），选择窗口将打开，并且精确选择退回地址或者销毁，然后按“保存”按钮。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/d8e93efd-2b94-42e5-8e08-40e064080f11.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/c07361fb-9d85-48c6-b416-c4ee02ca16ff.png.webp)

Q2：如何查看平台SKU？

A：登录WB卖家中心，点击"商品与价格" → "商品详情页" → "条形码=平台SKU"

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/9f0fef51-55c9-4fca-8ff9-ea3960b3950a.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/0e8b42a4-e869-4c47-acec-18b84f9c2f9a.png.webp)

若是多变种SKU，点击"商品与价格" → "商品详情页" → "条形码=平台SKU"，展示"多变种SKU"

!image.png

Q3：在导入映射的时候提示"店铺【】不存在或已停用"

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/2b548be8-cdb1-4594-9f05-95128565ccab.png.webp)

A：再导入的表格时需填写这两列信息

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/e38c5ea3-67c3-4e19-9334-4b26e5d02aa1.png.webp)

Q4：在处理订单的时候，提示"系统当前分配库存繁忙，请稍后重试!"

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/c2d6abfb-c7b0-4253-bb2e-9344b472303e.png.webp)

A:由于商品SKU没有填写数量，需要点击"订单列表" → 找到需要处理的订单 → 点击"修改" → 在"商品"输入对应SKU数量

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/f2ea9483-3c85-4e5e-adaf-82376ab7d788.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/8bb630c0-c5f7-4511-860e-8cefdce1568c.png.webp)

Q5：在审核映射的时候提示"未匹配到SKU对应关系"

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/2ef9f3bb-a24c-4d37-aed6-b0dec2d94436.png.webp)

A：映射关系错误，请检查当时填写平台SKU与平台条形码是否一致

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/d77db848-8540-405a-84be-7c3156f6d12a.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/6140075a-1e27-44fd-8120-c3bc468d31b2.png.webp)

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/1023e1bc-c26b-47fe-bbca-8ba17c516064.png.webp)

## 步骤6

将实际库存中的商品上传至平台

如有任何疑问，欢迎联系 CEL 相关业务负责人。

## 常见问题

1\. 费用是多少？

费用为 48 RMB/kg + 30 RMB/件。

2\. 如何在系统中显示发货？

目前在 WB 卖家后台暂时无法显示发货信息。您只需在 OMS CEL 中操作发货，Wildberries 平台上无需额外操作。

3\. API 令牌在哪里可以找到？

在为 Wildberries 设置 API 集成时，您需要创建 API 令牌，可在“API 集成”栏目中查看。

获取令牌的步骤：点击“创建新令牌”→ 输入任意 Token 名称并选择“内容 + FBS”→ 系统将生成令牌。

将该令牌填入 OMS CEL 系统的 “token” 字段即可完成店铺授权。

注意事项：创建 API 令牌时，不要勾选“测试”和“只读”；如果在创建后未及时复制 令牌，请删除并重新创建；

在 OMS CEL 系统使用令牌期间，不要在 WB卖家后台删除该令牌，否则系统将无法获取 Wildberries 的订单、标签和供货信息。

4\. 哪里可以查看商品库存？

目前 WB 卖家后台暂不支持查看送至合作仓库的库存，您只能在 CEL 订单管理系统中查看库存情况。

5\. 如何将 Wildberries 添加到 OMS CEL 系统？

首先在“API 集成”栏目中创建 API 令牌（点击“创建新令牌”→ 输入令牌名称 → 选择“内容 + FBS”→ 生成令牌）。

然后登录 OMS CEL 系统，进入“平台账户管理”，选择 Wildberries，填写店铺名称与 API 令牌并点击“确认”完成授权。

最后点击“开始下载”，系统会自动获取已付款但未发货的订单。

6\. 如何导入授权前已创建的订单？

点击“下载订单”，选择时间范围即可批量导入授权前的订单；如需导入指定订单，可选择日期、时间并输入订单号。

若订单无法导入，请检查令牌是否正确，必要时点击“修改”更新令牌。

7\. 授权 Wildberries 店铺到 OMS CEL 系统时出现错误怎么办？

这类错误通常是令牌输入不正确造成的，例如多输入了空格。

请重新授权店铺：点击“修改”，输入正确的令牌并点击“确认”，无需更改店铺名称。

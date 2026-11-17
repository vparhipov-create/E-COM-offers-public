# 如何管理价格与优惠

Source: https://seller.wildberries.ru/instructions/ch/ch/material/how-to-manage-item-prices-china
Retrieved: 2026-11-17

更新日期 11/11/2026

如何管理价格与优惠

您可以在“价格与折扣”页面管理商品价格。为此，请在卖家后台顶部菜单中将鼠标悬停在“商品与价格” → “价格与折扣”。

只有在套餐定制器的“商品不同尺码不同价格”选项已启用时，才能为商品的不同尺码设置不同价格

## 如何设置或编辑价格与优惠

您可以通过Excel表格和API手动更改价格与优惠：

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/60c1ef5b-ffd3-4fe7-ba4b-77f0c76092af.png.webp)

### 手动修改

1. 点击“编辑“

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/dca3b0ca-a7c2-4733-8987-6797cb7f27c0.png.webp)

表格中将可以编辑“零售价”和“卖家折扣”列。“折扣价”列中的数据将自动重新计算。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/c82d3bee-59bb-438f-8f99-1dbd1c1d6c76.png.webp)

1.  为所需商品输入新价格和折扣。
2.  点击屏幕右上角的“保存”按钮。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/db518834-778d-4d49-bad0-7a3eef447f7b.png.webp)

1.  在打开的窗口中，检查是否所有内容都填写正确，然后点击“保存”。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/a0e69e66-49bf-4179-b437-80f87f103779.png.webp)

通过筛选器，您可以找到：

- 无价格的商品 — 即使有库存，这些商品也不会被买家看到；
- 有库存的商品 — 例如，可以检查它们的价格；
- 特定类目或品牌的商品 — 例如，为其设置季节性折扣。

### 使用Excel模板修改

只有在您的商品数量不超过1,000,000（不同商品编号）时，才能使用此方法更新价格。如果有更多商品，请使用API更新价格。为此，请使用“价格和优惠”部分中的方法。

模板中包含所有商品，因此即使您只想更新超过1,000,000个商品中的一部分，也无法使用该模板。如需更新价格和折扣：

1. 点击“Excel操作”，然后选择“通过Excel更新”。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/0d13431b-9b42-4dff-93ea-5b76d7fb06ab.png.webp)

1. 在打开的窗口中，点击“生成模板”，然后点击“下载模板”。包含所有商品信息的文件将下载到您的电脑上。

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/41f77c3c-431e-48bc-8590-792072305dc2.png.webp)

1. 填写“新价格”和“新折扣”列。您可以仅指定价格或折扣。如果不想更改某些商品的价格或折扣，请将相应字段留空。
2. 上传填写好的模板：

对于珠宝首饰，可以为不同尺寸的产品设置不同的价格。为此，请选择“Excel操作“→ "通过Excel操作按尺寸更新”。接下来，按照上面描述的步骤进行，区别仅在于模板中会有“WB 尺寸 ID”和“尺寸名称”列。如果您的商品目录中没有此类商品，模板中会显示相关提示。

![](https://static-basket-02.wbbasket.ru/vol20/article-static/9f92e8b4-76f3-456b-a157-814be3d67f8a.webp.webp)

### 使用API修改

如果您的商品超过1,000,000个，请使用API，并参考“价格和优惠”部分中的方法。

## 买家在商品页面上看到的价格是如何形成的

您可在 WB 卖家后台的“ [价格和优惠](https://seller.wildberries.ru/discount-and-prices)”部分设置商品的价格和折扣，不过在 Wildberries 网站及移动应用中，买家看到的价格或许会有所差异。

![](https://static-basket-02.wbbasket.ru/vol20/article-static/9dda9347-c149-4345-b08c-8d34244bc66f.png.webp)

买家所看到的价格可能受以下因素影响：

- WB Club折扣。您可以为商品设置的额外折扣，面向 WB Club 的订阅买家开放。关于 WB Club 折扣的详细信息，您可查阅相关 [指南](https://seller.wildberries.ru/instructions/ch/ch/material/wb-club-discount-china)；
- 使用 WB 钱包付款的折扣。此折扣针对不同买家会呈现个性化差异，具体取决于买家在 Wildberries 应用中所看到的钱包状态；
- WB折扣，即常客优惠。这是Wildberries自费向买家提供的折扣。

## 检查更新

通常价格和折扣会在几分钟内更新，如果新价格或折扣存在错误，则不会改变。所有信息都可以在“变更历史”选项卡中找到。

在您更改价格或折扣后，在“ [变更历史](https://seller.wildberries.ru/discount-and-prices/update-history)”\- “已处理”选项卡中能够找到您的更新。

更新可能是以下状态：

- 已成功处理 — 所有商品的价格和折扣都已更新。
- 部分处理 — 某些商品的价格或折扣存在错误。对于没有错误的商品，价格和折扣已更新，此类商品的数量将显示在最后一列。
- 错误 — 所有商品的价格或折扣都存在错误，没有更新价格和折扣。

例如：

![image.png](https://static-basket-02.wbbasket.ru/vol20/article-static/0f06af7d-50bf-4204-b465-b05779faf21b.png.webp)

在“当前上传”选项卡中可能会有状态为“新”的更新记录 — 这些是 [促销日历](https://seller.wildberries.ru/dp-promo-calendar) 的折扣更新。点击对应行可以查看哪些商品的价格已更新以及哪些出现了错误。

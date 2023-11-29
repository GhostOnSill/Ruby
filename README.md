# 使用手册

### 买家操作

- 浏览产品列表

  用户可进入商品中心(/products)，浏览所有产品

  <img src="https://picdl.sunbangyan.cn/2023/11/29/3fc5bf1bb1e8e751497eadb91215fa0b.jpeg" title="" alt="2023-11-29-08-03-32-image" width="373">

  点击即可进入对应商品

  可以自由选择颜色，样式，尺寸，数量等

  <img src="https://picss.sunbangyan.cn/2023/11/29/e7d1d2e5bcc1a36888ebdcf63afcf59e.jpeg" title="" alt="2023-11-29-08-04-32-image" width="405">

- 添加到购物车

  在商品详情页中，可以选择颜色，样式，尺寸以及数量然后点击加入购物车，即可加入到用户的购物车

- 购物车内容生成订单

  在用户的购物车界面(/carts)，可以查看当前用户所有的创建的购物车商品列表，点击下单，在下单跳出的弹框中，可以确认商品信息，并且输入订单的具体信息，点击创建订单，即可生成对应产品的订单

  <img src="https://picst.sunbangyan.cn/2023/11/29/d364767424e9d5481b84140c936d0c26.jpeg" title="" alt="2023-11-29-08-05-13-image" width="424">

  <img src="https://picdl.sunbangyan.cn/2023/11/29/6ff1f25843232085d957dc93c9834855.jpeg" title="" alt="2023-11-29-08-08-41-image" width="316">

- 查看自己的订单列表

  在用户的我的订单界面可以查看当前用户的所有订单的信息

  ![2023-11-29-08-10-56-image](https://picdm.sunbangyan.cn/2023/11/29/c984a796083fcdbe640a2a2d44452ce3.jpeg)

- 订单操作（付款，确认收货，取消订单）

  订单有四种状态，等待支付，等待发货，订单已发货，订单已完成

  等待支付时用户可以选择付款

  订单已发货时用户可以选择确认收货，确认后，订单进入订单已完成状态。

  在订单已发货之前，用户可以选择取消订单，若已付款会弹出退款通知，不然则弹出成功取消

  ![2023-11-29-08-14-17-image](https://picdm.sunbangyan.cn/2023/11/29/acbd5754c85ba619da63f885a1ffc984.jpeg)

- 添加产品到收藏夹 将产品从收藏夹内删除

  在商品中心，收藏夹界面，以及商品详情页

  点击收藏，即可收藏产品，再点击一次，即可取消对产品的收藏

  ![2023-11-29-08-16-58-image](https://picdl.sunbangyan.cn/2023/11/29/4dac317c847a26088a8e0d878f597ee9.jpeg)

  <img src="https://picst.sunbangyan.cn/2023/11/29/553b5b92f3925fa414fed5951c2b074f.jpeg" title="" alt="2023-11-29-08-17-10-image" width="236">

- 浏览收藏夹

  访问（/favourites），即可浏览当前用户的所有收藏夹内产品的情况

  <img src="https://picst.sunbangyan.cn/2023/11/29/5476c631d6f7b49cc94399e1bd629d79.jpeg" title="" alt="2023-11-29-08-18-37-image" width="367">

### 管理员操作

- 添加/编辑/查看/删除产品

  在商品广场右边点击加入新商品

  <img src="https://picdm.sunbangyan.cn/2023/11/29/2b906d6f52fcecf46cb7d11dbec68778.jpeg" title="" alt="2023-11-29-09-24-43-1701221076638" width="453">
  <img src="https://picdl.sunbangyan.cn/2023/11/29/75dc8b58b05c148f6553403455a503c3.jpeg" title="" alt="2023-11-29-09-25-07-1701221104036" width="452">
  填表即可加入新商品，Color，Size，Type，可以用逗号分隔，即可加入多种商品款式，颜色，尺寸（**英文逗号！！！**）

- 查看所有订单列表

  在管理员界面下的订单管理(/orders）中可以查看所有的订单信息

- 处理订单（发货/删除）

  管理员在订单处于等待发货阶段时，可以点击进行发货，在订单完成之前，都可以取消订单

- <img src="https://picdl.sunbangyan.cn/2023/11/29/663034714251fecec325aa932dfab7a3.jpeg" title="" alt="2023-11-29-09-29-56-image" width="520">
  <img src="https://picdm.sunbangyan.cn/2023/11/29/65df692e87ab0836992ee36a2db03fa2.jpeg" title="" alt="2023-11-29-09-31-06-image" width="525">

# 附加设计

### 评论区

<img src="https://picdl.sunbangyan.cn/2023/11/29/4bd0c4c32e47c6142a1ddaf21aa34c6d.jpeg" title="" alt="2023-11-29-09-32-24-image" width="490">

除了游客，均可以在商品的讨论区中发表讨论帖，管理员以及发表该评论的用户，可以对讨论帖进行编辑与删除操作

### 权限管理

游客只可以查看商品广场，商品详情，以及商品讨论区。

用户可以使用上述提到功能。

管理员可以管理查看商品以及处理订单信息

⼀、题⽬
实现⼀个购物系统，要求具备以下功能：
1. ⽤户可以浏览商品，提供按商品名字搜索功能。
2. ⽤户可以下单购买某样商品（⽀付过程可以省略），购买成功后系统需要异步通知下游系统（如仓库 	系统、物流系统等，下游系统可简单实现）。
3. 提供后台管理⻚⾯录⼊商品，包括商品名称、商品描述、商品价格、库存等。
4. 要求记录⽤户访问⽇志，供审计使⽤。
⼆、实现要求
1. 前端使⽤Vue.js + elementUI，后台使⽤ AdonisJS 框架（AdonisJS 版本要求5.0以上）。 数据库使⽤ mysql，结合 AdonisJS 的 ORM 能⼒。
2. 设计时需要考虑必要的系统安全性。
3. 实现周期为5天左右。
4. 要求交付可运⾏的项⽬代码、必要的设计⽂档。

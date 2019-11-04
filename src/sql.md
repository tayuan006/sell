create table 'product_info' (
    'product_id' varchar(32) not null,
    'product_name' varchar(64) not null comment '商品名称',
    'product_price' decimal(8,2) not null comment '单价',
    'product_stock' int not null comment '库存',
   primary key('product_id'),
) comment '商品表';

create table 'product_category' (
    #类目名称、类目编号、修改时间、创建时间、
)

create table 'order_master' (
 # 买家地址、买家电话、买家名字、买家openId、总金额、
 # 订单状态’默认为0‘、支付状态“默认为0”
 primary key('order_id')
 key 'idx_buyer_openid' ('buyer_openid')
)

#注意和商品详情页的字段类型和长度一致
create table 'order_detail' (
#detailedID、订单id、商品id、商品名字、商品价格、商品数量、商品图片（缩略图的连接）
# 创建时间、修改时间、
# 主键 detailedId
# 索引 order_id


)
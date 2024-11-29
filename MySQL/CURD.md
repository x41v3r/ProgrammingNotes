# 1 创建

## 建表语句

```mysql
CREATE TABLE `表名` (
	`field01` decimal(20,0) DEFAULT NULL COMMENT '序号',
	`field02` varchar(100) DEFAULT NULL COMMENT '供应商',
	`field03` varchar(100) DEFAULT NULL COMMENT '内容',
	`field04` decimal(20,0) DEFAULT NULL COMMENT '付款金额',
	`field05` date DEFAULT NULL COMMENT '付款时间',
	`field06` varchar(100) DEFAULT NULL COMMENT '备注_明细'
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COMMENT='付款记录表';
-- 套用即可
```


# 2 更新


# 3 查询


# 4 读取









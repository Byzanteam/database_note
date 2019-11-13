# red_packets

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| message_type | varchar | 信息类型 |
| message_id | int | 信息类型 id |
| message_title | varchar | 消息标题 |
| user_id | int | 用户 id  |
| total_amount | decimal | 总金额 |
| status | int | 状态 |
| raw_responses | jsonb | 记录 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| user_name | varchar | 用户名字 |
| remark | text | 标记 |
| pack_params | jsonb | 参数 |
| mch_billno | varchar | 编号 |
| obtainment_gid | varchar | gid |


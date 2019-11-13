# red_packet_settings

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| message_type | varchar | 信息类型 |
| message_id | int | 信息类型 id |
| total_num | int | 总数 |
| random | boolean | 是否随机 |
| wishing | varchar | 期望 |
| act_name | varchar | 行为名称 |
| remark | varchar | 标记 |
| expired_at | timestamp | 过期时间 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| closed_at | timestamp | 关闭时间 |
| begin_per_amount | decimal | 起始金额 |
| end_per_amount | decimal | 结束金额 |
| send_name | varchar | 发送名字 |
| status | int | 状态 |
| expire_job_id | varchar | 过期任务 |


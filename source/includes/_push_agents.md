# push_agents

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| recipient_ids | int | 收件人 id |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| type | varchar | 类型 |
| pushable_id | int |  |
| pushable_type | varchar |  |
| status | int | 状态 |
| include_uncompleted | boolean |  |
| meta | jsonb |  |
| aborted_at | timestamp |  |
| scheduled_at | timestamp | 定时器 |
| push_package_id | int | 推送包 id |


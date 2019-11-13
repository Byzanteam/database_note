# pushes

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| type | varchar | 类型 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| interval | int | 间隔 |
| job_id | varchar | job id |
| completed_at | timestamp | 完成时间 |
| scheduled_at | timestamp | 定时器 |
| push_count | int | 推送总数 |
| push_agent_id | int | 推送端 id |
| scheduled | boolean | 是否循环 |
| recipient_types | varchar | 接收类型 |


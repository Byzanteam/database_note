# subscription_settings

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| user_id | int | 用户 id  |
| push_types | varchar | 推送类型 |
| subscriptions_on | varchar | 订阅 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| quiet_hours | jsonb | 静默时间 |
| push_job_id | varchar | 推送任务 id |


# subscriptions

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| subscriptionable_type | varchar | 订阅类型 |
| subscriptionable_id | int | 订阅类型 id |
| user_id | int | 用户 id |
| type | varchar | 类型 |
| push_type | int | 推送类型 |
| push_value | varchar | 推送值 |
| pending_item_ids | int | 悬挂任务 |
| last_push_at | timestamp | 最后推送时间 |
| push_job_id | varchar | 推送任务 id |


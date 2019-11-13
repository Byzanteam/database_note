# message_activities

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| message_type | varchar | 信息类型 |
| message_id | int | 信息类型 id |
| user_id | int | 用户 id  |
| content | text | 评论 |
| action | varchar | 记录 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| object_changes | jsonb | 改变 |


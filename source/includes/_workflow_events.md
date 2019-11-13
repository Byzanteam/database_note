# workflow_events

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| proposal_id | int | 方案 id |
| phase_id | int | 阶段 id |
| user_id | int | 用户 id  |
| status | int | 状态 |
| content | text | 评论 |
| cache | jsonb | 缓存 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| elec_signature | text | 签名 |


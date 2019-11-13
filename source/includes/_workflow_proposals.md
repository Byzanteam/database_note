# workflow_proposals

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| user_id | int | 用户 id  |
| approval_id | int | 通过 id |
| response_id | int | 记录 id |
| status | int | 状态 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| strategy_id | int | 策略 id |
| cache | jsonb | 缓存 |
| read | boolean | 是否可读 |
| current_phase_id | int | 当前阶段 id |
| candidate_strategy_ids | int | 备选策略 id |


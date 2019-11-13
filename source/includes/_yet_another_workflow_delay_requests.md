# yet_another_workflow_delay_requests

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| status | int | 状态 |
| requester_id | int | 请求者 id |
| requester_assignment_id | int | 请求者任务 id |
| assignment_id | int | 任务 id |
| data | jsonb | 数据 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| hourglass_id | int | 定时器 id |
| approve_result_alert_at | timestamp | 通过评论 |
| moment_id | int | moment id |


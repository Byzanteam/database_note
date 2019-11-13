# yet_another_workflow_assignments

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| assignee_id | int | 任务 id |
| vertex_id | int | 节点 id |
| status | int | 状态 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| journey_id | int | 流程 id |
| responses_count | int | response 数量 |
| response_id | int | 记录 id |
| next_vertices_ids_cache | int | 缓存的下个节点 id |
| read | boolean | 是否可读 |
| category | int | 分类 |
| user_flow_cache_id | int | 用户流程缓存 id |
| operation_data | jsonb | 操作数据 |
| current_duration_threshold | varchar | 当前过期时间 |
| flow_id | int | 流程 id |
| assignee_type | varchar | 指定类型 |


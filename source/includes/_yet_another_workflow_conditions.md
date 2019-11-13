# yet_another_workflow_conditions

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| position | int | 位置 |
| conditionable_type | varchar | 条件类型 |
| conditionable_id | int | 条件类型 id |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| judgements | jsonb | 判决 |
| edge_id | int | 边缘 id |


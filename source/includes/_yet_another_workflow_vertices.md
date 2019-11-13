# yet_another_workflow_vertices

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| name | varchar | 名字  |
| type | varchar | 类型 |
| operations | jsonb | 操作者 |
| metadata | jsonb | 元数据 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| graph_id | int | 图 id |
| out_edges_count | int | 边缘数量 |
| in_edges_count | int | 边数 |
| field_ids | int | 字段 id |
| flow_id | int | 流程 id |
| settings | jsonb | 设置 |
| responses_count | int | response 数量 |
| active_errors | jsonb | 错误信息 |
| deleted_at | timestamp | 删除时间 |


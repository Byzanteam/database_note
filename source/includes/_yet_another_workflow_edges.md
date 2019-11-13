# yet_another_workflow_edges

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| from_vertex_id | int | 上个节点 id |
| to_vertex_id | int | 下个节点 id |
| metadata | jsonb | 元数据 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| flow_id | int | 流程 id |
| graph_id | int | 图 id |
| conditions_count | int | 条件数量 |
| deleted_at | timestamp | 删除时间 |


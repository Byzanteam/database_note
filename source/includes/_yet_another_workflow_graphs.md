# yet_another_workflow_graphs

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| metadata | jsonb | 元数据 |
| ancestry | varchar | 继承层级 |
| ancestry_depth | int | 继承深度 |
| flow_id | int | 流程 id |
| name | varchar | 名字  |
| settings | jsonb | 设置 |
| active_errors | jsonb | 错误信息 |
| deleted_at | timestamp | 删除时间 |


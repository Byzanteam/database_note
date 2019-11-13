# workflow_approvals

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| name | varchar | 标题  |
| html_body | text | html 内容 |
| text_body | text | 文本内容 |
| author_id | int | 作者 id |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| status | int | 状态 |
| namespace_id | int | 空间 id |
| settings | jsonb | 设置 |
| responses_count | int | response 数量 |


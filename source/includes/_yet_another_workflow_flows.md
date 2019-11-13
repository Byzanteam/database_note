# yet_another_workflow_flows

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| name | varchar | 标题  |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| namespace_id | int | 空间 id |
| responses_count | int | response 数量 |
| settings | jsonb | 设置 |
| text_body | text | 文本内容 |
| html_body | text | html 内容 |
| status | int | 状态 |
| today_sn_count | int | sn 数量 |
| sn_prefix | varchar | 前缀 |
| cover | jsonb | 封面 |
| user_id | int | 用户 id  |
| logic_settings | jsonb | 逻辑设置 |
| original_id | int | 原 id |
| copy_mapping | jsonb | 复制路线 |
| cloned_from_id | int | 克隆 id |


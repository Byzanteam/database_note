# template_posts

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| name | varchar | 标题  |
| html_body | text | html 内容 |
| author_id | int | 作者 id |
| status | int | 状态 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| serialized_body | binary | 序列化内容 |
| published_at | timestamp | 发布时间 |
| published_as_id | int | 发布 id |
| namecard_id | int | 名片 id |
| comment_status | int | 评论状态 |
| text_body | text | 文本内容 |
| images | varchar | 图片 |
| settings | jsonb | 设置 |
| complete_creating_receipts_at | timestamp | 完成数据收集时间 |
| namespace_id | int | 空间 id |
| receipts_count | int | 收集数量 |
| completed_receipts_count | int | 收集数量 |
| responses_count | int | response 数量 |
| cloned_from_id | int | 克隆 id |


# forms

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| title | varchar | 标题 |
| description | text | 描述 |
| author_id | int | 作者 id |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| anonymous_allowed | boolean | 匿名开关 |
| submit_once | boolean |  |
| involved_queryable | boolean |  |
| status | int | 状态 |
| step_renderable | boolean |  |
| responses_count | int | response 数量 |
| after_submit_action | int |  |
| after_submit_show_message | text |  |
| after_submit_redirect_url | text |  |
| published_at | timestamp | 发布时间 |
| enable_appendable | boolean | 追加开关 |
| published_as_id | int | 发布 id |
| namecard_id | int | 名片 id |
| success_message | text |  |
| comment_status | int | 评论状态 |
| responses_limit | int |  |
| closed_at | timestamp | 关闭时间 |
| close_job_id | varchar |  |
| text_body | text | 文本内容 |
| response_required | boolean |  |
| images | varchar | 图片 |
| settings | jsonb | 设置 |
| complete_creating_receipts_at | timestamp | 完成数据收集时间 |
| namespace_id | int | 空间 id |
| receipts_count | int | 收集数量 |
| completed_receipts_count | int | 收集数量 |
| logic_settings | jsonb | 逻辑设置 |
| cloned_from_id | int | 克隆 id |
| push_agent_on_publish_attributes | jsonb | 推送参数 |


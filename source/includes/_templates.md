# templates

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| raw_body | text | 内容 |
| serialized_body | binary | 序列化内容 |
| compressed_css | text | css |
| javascript | text | js |
| type | varchar | 类型 |
| templateable_id | int | 模板类型 id |
| templateable_type | varchar | 模板类型 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| default | boolean | 默认值 |
| name | varchar | 名字  |
| scss | text | scss |
| compressed_js | text | js |
| enable_v2_layout | boolean | v2 模板开关 |
| raw_body_for_pc | text | pc 内容 |
| serialized_body_for_pc | binary | 序列化 pc 内容 |
| javascript_for_pc | text | pc js |
| compressed_js_for_pc | text | pc js |
| scss_for_pc | text | pc scss |
| compressed_css_for_pc | text | pc css |


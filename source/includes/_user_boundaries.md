# user_boundaries

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| organization_ids | varchar | 组织 id |
| user_tag_ids | int | 用户标签 id |
| user_tagged_type | int | 用户标签类型 |
| only_binded | boolean | 是否绑定 |
| overlord_type | varchar | 类型 |
| overlord_id | int | 类型 id |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| namespace_id | int | 空间 id |
| user_ids | int | 用户 id |
| status | int | 状态 |
| append_count | int | 追加数量 |
| cached_organization_ids | int | 缓存组织 id |
| cached_user_ids | int | 缓存用户 id |
| extra_boundary | jsonb | 其他绑定参数 |
| type | varchar | 类型 |


# responses

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| user_id | int | 用户 id  |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| involved_user_ids | int | 用户 id |
| involved_organization_ids | int | 组织 id |
| responseable_id | int | response 类型 id |
| responseable_type | varchar | response 类型 |
| cached_values | jsonb | 缓存字段 |
| organization_ids | int | 组织 id |
| cached_values_version | timestamp | 缓存字段版本 |


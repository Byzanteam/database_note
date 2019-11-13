# oauth_access_grants

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| resource_owner_id | int |  资源拥有者 id |
| application_id | int | 应用 id |
| token | varchar | token |
| expires_in | int | 过期时间 |
| redirect_uri | text | 重定向链接  |
| created_at | timestamp | 插入时间 |
| revoked_at | timestamp | 撤销时间 |
| scopes | varchar | 范围 |


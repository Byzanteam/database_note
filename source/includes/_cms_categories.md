# cms_categories

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| int | int | 主键 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| namespace_id | int | 空间 id |
| name | varchar | 名字 |
| depth | varchar | 深度 |
| description | varchar | 描述 |
| icon | varchar | 图标 |
| position | int | 位置 |
| hidden | bool | 是否隐藏 |
| involved_organization_ids | varchar | 组织 id |
| involved_user_tag_ids | varchar | 标签 id |
| external_link | text | 链接 |
| template_id | varchar | 模版 id |
| sort_type | varchar | 排序方式 |
| authorizable_id | varchar | 权限 id |
| cms_variables | varchar | 分类 |
| search_template_id | int | 搜索模版 |
| ancestry | varchar | 继承字段 |
| admin_ids | int | 管理员 |

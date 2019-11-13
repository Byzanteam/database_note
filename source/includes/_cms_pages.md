# cms_pages

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| int | int | 主键 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| title | varchar | 标题 |
| html_body | text | 页面内容 |
| category_id | int | 分类 id |
| description | varchar | 表述 |
| position | int | 位置 |
| external_link | text | 外部链接 |
| cover | varchar | 封面 |
| hidden | bool | 是否隐藏 |
| template_id | int | 模板 id |
| involved_user_tag_ids | int | 用户标签 id |
| involved_organization_ids | int | 组织 id |
| comment_status | int | 评论状态 |
| authorizable_id | int | 权限 id |
| cms_variables | varchar | cms 变量 |
| read_count | int | 阅读次数 |

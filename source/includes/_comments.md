# comments

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| int | int | 主键 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| author_id | int | 发布者 |
| commentable_id | int | 评论类型 |
| commentable_type | varchar | 评论类型 id |
| body | text | 评论内容 |
| status | int | 状态 |
| handled_user_id | int | 处理用户 id |
| replied_comment_id | int | 回复用户 id |

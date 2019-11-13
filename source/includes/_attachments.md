# attachments

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| int | int | 主键 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| key | varchar | key |
| name | varchar | 名字|
| size | varchar | 文件大小 |
| mime_type | varchar | 文件类型 |
| attachmentable_id | int | 关联外健 |
| attachmentable_type | varchar | 外健类型 |
| author_id | int | 上传者 id |
| file_extension | int | 文件路径 |
| extra_info | jsonb | 信息 |

# import_records

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| user_id | int | 用户 id  |
| status | int | 状态 |
| file | varchar | 文件 |
| recordable_id | int | 记录类型 id |
| recordable_type | 记录类型 |  |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| options | json | 选项 |
| type | varchar | 类型 |
| failure | jsonb | 失败 |
| success | jsonb | 成功 |
| original_filename | varchar | 原文件名字 |


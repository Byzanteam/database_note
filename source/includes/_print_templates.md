# print_templates

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| templateable_type | varchar | 模板类型 |
| templateable_id | int | 模板类型 id |
| payload | binary | payload |
| broken | boolean | 销毁 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| variables_payload | jsonb | 校验数据 |
| metadata | jsonb | 元数据 |


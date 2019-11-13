# wechat_media_articles

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| thumb_media_id | varchar | 媒体 id |
| author | varchar | 作者 |
| name | varchar | 标题  |
| content_source_url | varchar | 内容链接 |
| content | text | 评论 |
| digest | varchar | 概述|
| show_cover_pic | boolean | 是否展示封面 |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| cms_page_id | int | cms page id |
| wechat_media_mass_news_id | int | 微信媒体 id |
| wechat_ready_at | timestamp | 微信对接事件 |


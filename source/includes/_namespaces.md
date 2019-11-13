# namespaces

| 字段名称 | 字段类型 | 字段含义 |
| :-----: | :-----: | :-----: 
| id | int | 主键 |
| name | varchar | 名字  |
| created_at | timestamp | 插入时间 |
| updated_at | timestamp | 更新时间 |
| appid | varchar | appid |
| appsecret | varchar | appsecret |
| token | varchar | token |
| access_token | varchar | access_token |
| categories_public | boolean | 公开分类 |
| identifier_alias | varchar | 别名 |
| attendance_enable | boolean | 是否启用 |
| certificated_ip | inet | 认证 ip |
| push_phone | varchar | 推送手机 |
| menu_payload | json | 菜单 |
| category_menu_payload | json | 分类菜单 |
| logo | varchar | logo |
| signup_enable | boolean | 登录开关 |
| customer_service_reg | varchar | 客服服务 |
| customer_service_enable | boolean | 客服服务开关 |
| customer_service_prompt | text | 客服服务文本 |
| profile_required | boolean | 第三方链接 |
| admin_user_ids | int | 管理员 id |
| namecard_version | int | 名片版本 |
| namecard_enable | boolean | 名片开关 |
| superior_ids | int | 超管 id |
| template_message_id | varchar | 模板消息 id |
| site_name | varchar | 网站名字 |
| remote_responder_uri | varchar | 远程链接 |
| remote_responder_token | varchar | 远程链接 token |
| short_url_in_sms | boolean | 短链接 |
| identifier_case | int | 别名 |
| comment_enable | boolean | 评论开关 |
| brand_images_preferences | json | 图片设置 |
| unread_cover | varchar | 未读封面 |
| help_html | text | 帮助链接 |
| verify_with_name | boolean | 校验名字 |
| private_token | varchar | private token |
| authorization_info | jsonb | 授权信息 |
| domain_verify_file | varchar | 域名校验文件 |
| wxpay_settings | jsonb | 微信支付设置 |
| wxpay_pkcs12 | varchar | 微信支付文件 |
| push_interval | int | 推送 |
| settings | jsonb | 设置 |
| features | varchar | 功能 |
| custom_css | jsonb | 自定义 css |
| wx_template_settings | jsonb | 微信模板设置 |
| deleted_at | timestamp | 删除时间 |


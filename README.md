在您的 config.ini 文件中，您可以添加一个新的部分来存储多个账号的信息。以下是一个示例配置：
```
[settings]
like_probability = 0.02
reply_probability = 0.0
collect_probability = 0.02
max_topics = 10

[urls]
home_url = https://linux.do/
connect_url = https://connect.linux.do/

[wxpusher]
use_wxpusher = false
app_token =
topic_id =

[credentials]
username1 = your_username1
password1 = your_password1
username2 = your_username2
password2 = your_password2
username3 = your_username3
password3 = your_password3
# 可以继续添加更多账号...

```

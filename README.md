# bugku_checkin_scf
bugku自动签到，腾讯云函数。通过github第三方登录的方式，来登录 Bugku ctf平台进行签到。

### 脚本中需要配置：

+ githubcookie 

  不多说

+ your_ftqq_key

  发送微信通知

### scf 腾讯云函数：

运行环境版本选择Python3.6，触发我选择了定时`0 0 20-21 * * * *`。


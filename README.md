# webhook
[![Build Status](https://travis-ci.org/qq958691165/webhook.svg?branch=master)](https://travis-ci.org/qq958691165/webhook)

用于git的webhook服务,用法：<br>
  ````
  1.[c]npm install
  2.node index.js 或 npm run start
  3.配置config.json
  4.webhook地址:
    http://[ip]:[port]/webhook/[项目名]
  ````
  PS:<br>
+ 本程序配有后台设置页面如有需要请到<a href="#">http://[您的ip]:[设置的端口]</a>
+ 后台默认密码为123456，部署后请务必修改
+ 可将config.json的web选项改为false以关闭web管理(不影响webhook)
+ 强烈建议不要用根用户运行此程序，避免出现不必要的损失
+ 若有疑问请发邮件至958691165@qq.com

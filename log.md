# 日志信息

## 使用账号
```
[INFO] [tg-signer] 2025-01-01 06:20:28,917 signer.py 154 使用账号: my_account
```

## 添加消息回调处理函数
```
[INFO] [tg-signer] 2025-01-01 06:20:33,961 core.py 525 为以下Chat添加消息回调处理函数：[5617554994, 7152090568, 7390099785, 6811705378, 6561491140, 7184649669, 6880480833, 7930300752, 6779714191, 7608602072, 7590446422, 6690063578, 6086709659]
```

## 当前时间
```
[INFO] [tg-signer] 2025-01-01 06:20:35,540 core.py 532 当前时间: 2025-01-01 06:20:35.540776+08:00
```

## 消息删除
```
[INFO] [tg-signer] 2025-01-01 06:20:35,822 core.py 337 Message「/sign」 to 5617554994 will be deleted after 8 seconds.
[INFO] [tg-signer] 2025-01-01 06:20:35,823 core.py 340 Waiting...
```

## 收到消息
```
[INFO] [tg-signer] 2025-01-01 06:20:36,719 core.py 596 收到来自「zhihu_bot」的消息: 
Message: 
  text: 🎉恭喜您, 签到成功, 奖励 1 积分
🔥您目前拥有 4 积分, 感谢您对 @zhihu_bot 的支持
```

## 忽略未配置选项
```
[INFO] [tg-signer] 2025-01-01 06:20:36,719 core.py 614 忽略，未显式配置需要点击按钮的选项
```

## 消息删除记录
```
[INFO] [tg-signer] 2025-01-01 06:20:44,088 core.py 343 Message「/sign」 to 5617554994 deleted!
```

## 其他消息处理示例

### 消息发送及响应处理
```
[INFO] [tg-signer] 2025-01-01 06:20:44,868 core.py 337 Message「/signin」 to 7152090568 will be deleted after 8 seconds.
[INFO] [tg-signer] 2025-01-01 06:20:44,868 core.py 340 Waiting...
[INFO] [tg-signer] 2025-01-01 06:20:46,138 core.py 596 收到来自「ppsgk_bot」的消息: 
Message: 
  text: 🎉🎉🎉 恭喜您, 签到成功, 奖励 1 积分 🎉🎉🎉
您目前拥有 12 积分, 感谢您对  @ppsgk_bot 的支持
  InlineKeyboard: 
   👤 我的账户 | 💰 积分充值 | 
```
```
[INFO] [tg-signer] 2025-01-01 06:20:46,138 core.py 614 忽略，未显式配置需要点击按钮的选项
[INFO] [tg-signer] 2025-01-01 06:20:53,182 core.py 343 Message「/signin」 to 7152090568 deleted!
```

### 连续签到处理
```
[INFO] [tg-signer] 2025-01-01 06:20:53,962 core.py 337 Message「/checkin」 to 7390099785 will be deleted after 8 seconds.
[INFO] [tg-signer] 2025-01-01 06:20:53,962 core.py 340 Waiting...
[INFO] [tg-signer] 2025-01-01 06:20:54,347 core.py 596 收到来自「jrsgk1_bot」的消息: 
Message: 
  text: ️️🎉签到成功！您获得了 5 积分！您的邀请链接：
https://t.me/jrsgk1_bot?start=Nzg1MTEwOTgyNw==

当前账户余额：18 分
已邀请用户数：0 人
获得的总积分：0 分

邀请新用户注册，每成功邀请一位可获得 10 积分！
  InlineKeyboard: 
   邀请领积分 | 
```
```
[INFO] [tg-signer] 2025-01-01 06:20:54,347 core.py 614 忽略，未显式配置需要点击按钮的选项
[INFO] [tg-signer] 2025-01-01 06:21:02,230 core.py 343 Message「/checkin」 to 7390099785 deleted!
```

## 其他消息记录
```
...
```
### 完成度统计与响应---
```
[INFO] [tg-signer] 2025-01-01 06:22:33,191 core.py 549 最多等待300秒，用于响应可能的键盘点击...
[INFO] [tg-signer] 2025-01-01 06:22:33,191 core.py 557 Done
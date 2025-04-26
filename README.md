## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Mar  5 10:11:46 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 00:51:39 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 00:51:56 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 00:39:58 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 00:44:08 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 00:42:50 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 00:52:04 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 00:51:22 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 00:52:08 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 00:51:17 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 00:51:01 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 00:55:50 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 00:52:02 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 00:52:29 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 00:51:28 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 00:52:44 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 00:51:11 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 00:56:25 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 00:54:20 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 00:53:06 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 00:52:43 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 00:52:32 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 00:52:40 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 00:52:09 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 00:57:16 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 00:56:00 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 00:59:47 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 00:53:47 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 00:53:11 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 00:52:41 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 00:52:02 UTC 2025
- Auto Sign-in run successful on Sun Apr  6 00:56:51 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 00:55:14 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 00:52:57 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 00:53:24 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 00:53:21 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 00:53:54 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 00:52:53 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 02:23:31 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 00:56:40 UTC 2025
- Auto Sign-in run successful on Tue Apr 15 00:55:08 UTC 2025
- Auto Sign-in run successful on Wed Apr 16 00:55:00 UTC 2025
- Auto Sign-in run successful on Thu Apr 17 00:53:51 UTC 2025
- Auto Sign-in run successful on Fri Apr 18 00:53:22 UTC 2025
- Auto Sign-in run successful on Sat Apr 19 00:51:46 UTC 2025
- Auto Sign-in run successful on Sun Apr 20 00:58:32 UTC 2025
- Auto Sign-in run successful on Mon Apr 21 00:57:11 UTC 2025
- Auto Sign-in run successful on Tue Apr 22 00:54:29 UTC 2025
- Auto Sign-in run successful on Wed Apr 23 00:55:03 UTC 2025
- Auto Sign-in run successful on Thu Apr 24 00:55:02 UTC 2025
- Auto Sign-in run successful on Fri Apr 25 00:54:51 UTC 2025
- Auto Sign-in run successful on Sat Apr 26 00:53:15 UTC 2025

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
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:44:23 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:50:23 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:48:08 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:46:30 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:46:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:45:51 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:45:50 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 00:45:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 00:51:33 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 00:48:29 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 00:46:41 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 00:50:42 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 00:46:21 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 00:46:49 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 00:51:07 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 00:49:39 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 00:48:00 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 00:46:47 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 00:47:10 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 00:51:57 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 00:45:22 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 00:51:16 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 00:49:00 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 00:45:05 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 00:45:18 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 00:45:18 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 00:45:05 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 00:44:12 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 00:49:41 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 00:47:06 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 00:44:48 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 00:45:48 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 00:45:57 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 00:49:53 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 00:48:22 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 00:53:01 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 00:51:31 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 00:49:53 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 00:48:52 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 00:48:59 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 00:50:21 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 00:47:14 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 00:53:26 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 00:51:21 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 00:50:17 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 00:50:48 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 00:50:56 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 00:50:50 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 00:48:56 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 00:59:55 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 00:53:05 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 00:52:18 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 00:52:06 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 00:51:59 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 00:51:30 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 00:51:03 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 00:55:54 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 00:53:39 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 00:52:54 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 00:52:11 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 00:51:48 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 00:52:39 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 00:50:14 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 00:56:05 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 00:53:55 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 00:52:02 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 00:49:54 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 00:50:24 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 00:46:52 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 00:46:02 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 00:51:54 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 00:48:46 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 00:46:41 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 00:45:36 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 00:45:52 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 00:46:29 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 00:45:09 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 00:52:18 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 00:48:59 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 00:46:14 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 00:52:29 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 00:46:11 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 00:46:37 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 00:45:30 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 00:52:01 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 00:50:02 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 00:47:27 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 00:47:15 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 00:47:04 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 00:48:36 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 00:47:13 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 00:52:42 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 00:51:12 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 00:44:27 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 00:45:37 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 00:45:03 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 00:44:53 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 00:43:52 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 00:50:06 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 00:46:40 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 00:44:57 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 00:46:38 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 00:45:31 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 00:45:23 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 00:43:48 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 00:47:04 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 00:47:01 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 00:45:43 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 00:45:35 UTC 2025
- Auto Sign-in run successful on Thu Jan 30 00:44:31 UTC 2025
- Auto Sign-in run successful on Fri Jan 31 00:45:43 UTC 2025
- Auto Sign-in run successful on Sat Feb  1 00:49:46 UTC 2025
- Auto Sign-in run successful on Sun Feb  2 00:49:07 UTC 2025
- Auto Sign-in run successful on Mon Feb  3 00:47:13 UTC 2025
- Auto Sign-in run successful on Tue Feb  4 00:45:44 UTC 2025
- Auto Sign-in run successful on Wed Feb  5 00:46:15 UTC 2025
- Auto Sign-in run successful on Thu Feb  6 00:46:43 UTC 2025
- Auto Sign-in run successful on Fri Feb  7 00:46:33 UTC 2025
- Auto Sign-in run successful on Sat Feb  8 00:44:58 UTC 2025
- Auto Sign-in run successful on Sun Feb  9 00:50:20 UTC 2025
- Auto Sign-in run successful on Mon Feb 10 00:47:57 UTC 2025
- Auto Sign-in run successful on Tue Feb 11 00:46:20 UTC 2025
- Auto Sign-in run successful on Wed Feb 12 00:46:32 UTC 2025
- Auto Sign-in run successful on Thu Feb 13 00:47:09 UTC 2025
- Auto Sign-in run successful on Fri Feb 14 00:46:27 UTC 2025
- Auto Sign-in run successful on Sat Feb 15 00:45:36 UTC 2025
- Auto Sign-in run successful on Sun Feb 16 00:51:53 UTC 2025
- Auto Sign-in run successful on Mon Feb 17 00:50:02 UTC 2025
- Auto Sign-in run successful on Tue Feb 18 00:46:10 UTC 2025
- Auto Sign-in run successful on Wed Feb 19 00:46:51 UTC 2025
- Auto Sign-in run successful on Thu Feb 20 00:47:21 UTC 2025
- Auto Sign-in run successful on Fri Feb 21 00:47:40 UTC 2025
- Auto Sign-in run successful on Sat Feb 22 00:45:19 UTC 2025
- Auto Sign-in run successful on Sun Feb 23 00:51:58 UTC 2025
- Auto Sign-in run successful on Mon Feb 24 00:49:51 UTC 2025
- Auto Sign-in run successful on Tue Feb 25 00:48:23 UTC 2025
- Auto Sign-in run successful on Wed Feb 26 00:47:53 UTC 2025
- Auto Sign-in run successful on Thu Feb 27 00:48:21 UTC 2025
- Auto Sign-in run successful on Fri Feb 28 00:48:22 UTC 2025
- Auto Sign-in run successful on Sat Mar  1 00:53:09 UTC 2025
- Auto Sign-in run successful on Sun Mar  2 00:52:27 UTC 2025
- Auto Sign-in run successful on Mon Mar  3 00:51:01 UTC 2025
- Auto Sign-in run successful on Tue Mar  4 00:49:43 UTC 2025
- Auto Sign-in run successful on Wed Mar  5 00:51:35 UTC 2025
- Auto Sign-in run successful on Wed Mar  5 09:07:49 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 00:59:07 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 00:59:52 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 00:46:17 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 00:51:55 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 00:50:49 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 00:59:49 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 00:59:05 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 00:59:59 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 00:59:08 UTC 2025

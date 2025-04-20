# 博士论文资料汇总（动图需要加载，请耐心等待片刻）

展示并上传了：论文中使用到的自建数据集、已经落地并商用化的相关应用及重要典型实验过程的实况视频，根据论文章节进行了分类。

# 第三章 非结构化场景照度变化下的目标检测方法
注意：其中MIVD数据集中的第2/3类，由于数据集文件夹过大（分别为11.8GB和6.37GB），无法上传到github上，我们将其上传至百度网盘，并共享了链接，点开MIVD文件夹对应的子文件夹可以找到永久分享的下载链接。

![4月19日](https://github.com/user-attachments/assets/018010ff-1181-4988-b594-3fad285aef0f)![image](https://github.com/user-attachments/assets/d1a8650c-2c4a-4699-8c41-bc39e66505fa)![111](https://github.com/user-attachments/assets/cbd48e77-f820-46bc-9b63-0ee92fae3b9a)

ACDet零样本检测效果（部分场景，和MIVD数据集中“2nd products-Grayscale images dataset”相似场景）

[点击观看视频-基于ACDet的实际工业视觉检测实际应用实况（智慧物流、仓储、医药配送行业）](https://www.bilibili.com/video/BV1p556zKEMC/?spm_id_from=333.1387.homepage.video_card.click)

# 第四章 抗遮挡及目标消失视觉长期跟踪方法

![4月20日(6)](https://github.com/user-attachments/assets/dfab4abe-1db2-4500-9bad-34b2773afb2a)![4月19日 (2)(2)](https://github.com/user-attachments/assets/e4b838f7-37fd-4378-9867-9fc003bb0be1)![4月20日 (2)(5)](https://github.com/user-attachments/assets/f3fd9289-2f9b-4b82-8f17-1a08c841f1b4)![控制跟随模拟火源](https://github.com/user-attachments/assets/02b7f821-778b-4dc7-9f3b-067f7d999ba6)

图片分别为：基于SFC-RT框架的复合机器人跟踪主目标协助巡检任务验证；主目标形态变化/环境光照变化/多目标干扰情况下跟随巡检；复合机器人底盘跟随模拟火源测试；机械臂根据跟踪模拟火源随动模拟灭火测试


# 第五章 多传感器融合定位建图及导航方法

![小尺度建图](https://github.com/user-attachments/assets/d6ad25d2-5686-46e9-9d7a-1ce50d49b3ef) ![4月8日(1)](https://github.com/user-attachments/assets/dacf7e1c-b4bc-4cea-8373-4ace9495a8b4)

小尺度室内工业场景定位建图![image](https://github.com/user-attachments/assets/af002865-377b-4f48-ad3e-0aac0cc18a19)大尺度校园定位建图

![4月20日 (2)(14)](https://github.com/user-attachments/assets/0a52402d-860f-40fc-8371-debb9195e5e2)![image](https://github.com/user-attachments/assets/898ca18d-9dbe-4cf6-894e-2cb4738794a5)
![4月20日 (2)(10)](https://github.com/user-attachments/assets/a352047c-6e3c-4a7a-a316-de2fe17e1f39)

灭火救援任务自主导航![image](https://github.com/user-attachments/assets/c5232d42-42e0-4d01-95ff-85a65b41a4d8)搬运生产任务自主导航

# 第六章 基于视觉感知的运动目标分类及控制抓取方法

1.多视觉模版特征匹配的密集分类标签识别及信息提取方法

[点击观看视频-基于SURF-THNSW的多面并行分类信息提取工业场景实际应用实况（3C行业）](https://www.bilibili.com/video/BV1p556zKEws/?spm_id_from=333.1387.homepage.video_card.click)

2.复合机器人抓取测试

![动态抓取](https://github.com/user-attachments/assets/8b559baa-351d-4af8-954d-56a8974d0a7a)![静态抓取3](https://github.com/user-attachments/assets/e2e219ba-e72f-4b26-a5ee-68bee31c97fa)![静态抓取2](https://github.com/user-attachments/assets/2aba5c25-1fe9-45a5-9fa4-32884d63c5d4)![静态抓取](https://github.com/user-attachments/assets/54277403-bed2-409d-8605-aeabf42a30be)![货架抓取](https://github.com/user-attachments/assets/3bfe84cf-f9d8-4be7-9b7d-2fe8646a08e9)

匀速运动目标抓取![image](https://github.com/user-attachments/assets/64fc0682-46e7-4b4a-bacd-9ea3ec7b40dd)静态弹夹拆卸![image](https://github.com/user-attachments/assets/464e2162-5e55-407c-b777-91dfad2e3263)静态多目标抓取![image](https://github.com/user-attachments/assets/ddcc9409-0dc6-4300-a452-ad23d5053c99)货架内静态分类抓取

# 其他 关于过去一些相关项目和未来将要研究的方向

图（a）展示了过去为某半导体芯片厂商设计的RFID纯移动地面机器人，用以辅助输送装载芯片的弹夹到指定区域。但是由于没有协作机械臂，需要人为辅助，且是通过中央调度系统下发任务的。

因此，作者根据日益广泛的需求，对复合机器人开展了深入的研究。目前及未来将要进行的工作之一，就是用复合机器人实现图（b）的效果，即分布式集群纯自主工作模式。利用视觉感知与IIVL-LM去实现自主移动，到达指定位置后通过视觉感知估计设备开关位姿，自动执行上下货的末端精确动作执行。

![过去做的](https://github.com/user-attachments/assets/91d256c9-6adb-4db1-92ff-5f8a9fb48c82)![image](https://github.com/user-attachments/assets/516e29f1-7163-4dbc-94d9-0938a6e30435)![未来研究方向](https://github.com/Chenlu-CN/GIF/blob/def75dcf526055a512a0ed77d0e3b22d234c00ff/%E6%9C%AA%E6%9D%A5%E5%81%9A%E7%9A%84.gif)























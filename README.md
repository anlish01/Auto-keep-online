# Auto-keep-online

此脚本是基于workers环境，定时访问网页，包括间断访问和不间断访问两种模式一起运行，以保证容器活跃。

# 使用说明 
1：workers文件夹里worker.js为cloudflared workers使用，复制整个代码到新建的workers里，修改需要访问的链接部署

2：在“设置”---”触发事件“菜单里设置访问频率，例如2分钟，保存即可，可开启日志查看是否运行，看下图
![image](https://github.com/user-attachments/assets/09e2474d-cf43-472e-a4ac-0df6504739e7)

3：可以添加环境变量
![PixPin_2024-12-19_18-16-11](https://github.com/user-attachments/assets/dbf1a840-55f5-4ed9-a662-8d3588a90431)

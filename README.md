
# 程序完全免费和本地化运行 

# 一键安装：
用root登录ssh执行：
```
curl -fsSL https://gist.githubusercontent.com/ciyahu/0fe599cd5ee83963992ed15eeeaf237f/raw/wemate.sh | bash
```
（可完整安装teslamate，也可单独增加wemate，一键升级teslamate3.0，一键修复） <br>
teslamate设置和使用请参考官网，新安装的teslamate会数据不全，多充电几次后即可正常  
登录ip:7777进入web管理，首次运行默认web密码teslamate 

# 更新   <br>   
2026.4.7 &nbsp;&nbsp; Bug修复，微信claw渠道增加ai api <br>
2026.4.4 &nbsp;&nbsp; 围栏电价Bug修复，添加导出记录测试 <br>
2026.4.3 &nbsp;&nbsp; 增加停车缴费提醒，阿里云盘备份按月分类，Bug修复 <br>
2026.4.1 &nbsp;&nbsp; 增加自动升级多地址拉取，Bark推送增加日报周报月报，底部增加实用按钮(陆续还会加)，Ui微调，bug修复 <br>
2026.3.31 &nbsp;&nbsp; 增加入场动画，增加充电费用分时电价 <br>
2026.3.30 &nbsp;&nbsp; 增加充电费用围栏 <br>
2026.3.29 &nbsp;&nbsp; Bark推送行程和充电增加地图和必要信息，Ui调整，BUG修复 <br>
2026.3.26 &nbsp;&nbsp; 修复部分配置修改后没有立即生效的BUG；微信ClawBot测试 <br>
2026.3.24 &nbsp;&nbsp; 增加grafana双地图，需再汉化一次 <br>
2026.3.24 &nbsp;&nbsp; 更新yml镜像地址，3000,4000端口默认中文 <br>
2026.3.23 &nbsp;&nbsp; 大幅提升页面加载速度 <br>
2026.3.21 &nbsp;&nbsp; 日报周报月报优化，行程轨迹优化 <br>
2026.3.20 &nbsp;&nbsp; 增加了彩色轨迹，自定义卡片行程可直接点击详情 <br>
2026.3.18 &nbsp;&nbsp; 优化数据库合并，数据库合并已经基本完善 <br>
2026.3.16 &nbsp;&nbsp; 修复了数据库闭合、合并、恢复后不自动重算日历和足迹的BUG，提升了页面加载速度 <br>
2026.3.15 &nbsp;&nbsp; 增加了数据库合并和未闭合记录的闭合 <br>
2026.3.10 &nbsp;&nbsp; 界面优化,BUG修复 <br>
2026.3.6 &nbsp;&nbsp; 增加了grafana重置并汉化,增加了3D模型测试,增加了配置上传阿里云 <br>
2026.3.3 &nbsp;&nbsp; 适配teslamate 3.0，增加数据库恢复时强制清空 <br>
2026.2.11 &nbsp;&nbsp; bug修复,ui微调,grafana汉化增强 <br>
2026.2.9 &nbsp;&nbsp; ui,时间轴,自定义卡片等大幅优化 <br>
2025.12.29 &nbsp;&nbsp; 2025年度总结 <br>
2025.12.9 &nbsp;&nbsp;&nbsp; bug修复 <br>
2025.12.4 &nbsp;&nbsp;&nbsp; ui优化,Grafana重复面板修复 <br>
2025.12.1 &nbsp;&nbsp;&nbsp; 新Ui增加自定义卡片,arm自动更新修复,增强grafana汉化 <br>
2025.11.29 &nbsp; 增加新Ui <br>
2025.11.25 &nbsp; 时间轴增加点击显示地图和数据 <br>
2025.11.24 &nbsp; 增加从阿里云一键恢复数据库，时间轴界面增加元素 <br>
2025.11.23 &nbsp; Grafana汉化和切换为高德地图 <br>
2025.11.23 &nbsp; 增加原版teslamate国内地址修复 <br>
2025.10 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 增加数据库定时自动备份到本地和阿里云 <br>
2025.9 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 增加docker管理和wemate自动更新 <br>
2025.8.24 &nbsp;&nbsp; 增加了web管理页面的内网穿透功能 <br>
2025.8.14 &nbsp;&nbsp; bug修复，增加了全平台支持(ARM64,apple等)，增加了地理围栏报警，增加了车辆编号选择 <br>
2025.8.8 &nbsp;&nbsp;&nbsp;&nbsp; bug修复，增加停车能量损失，增加管理页面ios轻应用(safari打开7777发送到桌面会生成轻应用) <br>
2025.8.6 &nbsp;&nbsp;&nbsp;&nbsp; 微信推送已支持内网穿透和ip中转，任何网络环境都可稳定使用

# 预览   <br> 
<!-- 设置图片宽度为 300px -->
<img src="https://github.com/user-attachments/assets/3e8addbb-c344-424f-9012-7bbee8b592ff?raw=true" alt="微信图片_20250809110339" width="300" /> <!-- 修改：替换为 HTML img 标签，添加 width 属性 -->
<img src="https://github.com/user-attachments/assets/3e5d0972-b273-4d8f-ab20-ab7812820cc4?raw=true" alt="微信图片_20250809110343" width="300" /> <!-- 修改：替换为 HTML img 标签，添加 width 属性 -->
<img src="https://github.com/user-attachments/assets/6288dd25-2197-463b-9be3-97bf9ff7da42?raw=true" alt="微信图片_20250809110348" width="300" /> <!-- 修改：替换为 HTML img 标签，添加 width 属性 -->
<img src="https://github.com/user-attachments/assets/da70d0e1-d95d-4150-b62d-178ad09f1af5?raw=true" alt="微信图片_20250809110348" width="300" /> <!-- 修改：替换为 HTML img 标签，添加 width 属性 -->
<img src="https://github.com/user-attachments/assets/103cf59d-e793-4298-979b-ae881e0d563d?raw=true" alt="微信图片_20250809110356" width="300" /> <!-- 修改：替换为 HTML img 标签，添加 width 属性 -->
<img src="https://github.com/user-attachments/assets/16282f0f-b69a-49f9-89c7-fbb7d53fc46b?raw=true" alt="微信图片_20250728200248" width="300" /> <!-- 修改：替换为 HTML img 标签，添加 width 属性 -->



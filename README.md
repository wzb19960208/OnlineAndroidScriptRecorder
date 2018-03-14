# OnlineAndroidScriptRecorder
本科毕业设计·在线Android脚本录制与回放工具

## 实现功能
### Android设备投屏显示在Web页面
使用MiniCap不断截图上传到Socket服务器，服务同解析图片数据使用WebSocket实时转发到页面

### 在Web端在线控制Android设备
捕捉页面的鼠标事件，通过WebSocket实时发送到服务端，使用cmd执行adb命令

### 脚本录制
通过鼠标事件转换为屏幕坐标，进行录制

### 回放脚本
根据脚本文件，执行adb命令

### 其他功能
 - 上传Apk
 - 自动安装
 - 自动打开Launch-Activity


## 演示视频
[演示视频](https://www.bilibili.com/video/av20555963/)

## 博文地址

<https://xugaoxiang.com/2021/06/30/yolov5-pyqt5>

## 代码执行

项目中使用`YOLOv5`的v5.0版本，界面文件是`project.ui`

```
pip install -r requirements.txt
python main.py
```

启动界面

![yolov5 pyqt5](data/screenshot_app.png)

图片检测

![yolov5 pyqt5](data/screenshot_img.png)

视频检测

![yolov5 pyqt5](data/screenshot_video.gif)

摄像头检测

![yolov5 pyqt5](data/screenshot_camera.gif)

图片处理后，预测结果保存在`prediction.jpg`

视频或者摄像头处理后，预测结果保存在`prediction.avi`

## exe打包

参考我的博文 <https://xugaoxiang.com/2021/10/13/yolov5-to-exe/>

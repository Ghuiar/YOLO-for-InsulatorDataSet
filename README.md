# YOLO-for-InsulatorDataSet
用YOLO对绝缘子数据集进行目标检测

## DataSet
>InsulatorDataSet包含绝缘子的图片以及目标和故障的标记。详细内容请看
>[InsulatorDataSet][1]

## Usage
>将insulatorDataSet2YOLO.py放到数据集目录下即可。insulatorDataSet2YOLO.py会>自动将原先的VOC数据集格式转化成成YOLO格式并划分好训练以及验证。yolov8训练该
>数据集可以参考[ultralytics.com官方文档][2]














[1]:https://github.com/InsulatorData/InsulatorDataSet
[2]:https://docs.ultralytics.com/modes/train/

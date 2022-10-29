# yolov7-face


| Method           |  Test Size | Easy  | Medium | Hard  | Link  |
| -----------------| ---------- | ----- | ------ | ----- | ----- |
| yolov7-tiny-leak | 640        | 93.2  | 91.3   | 83.0  | [google](https://drive.google.com/file/d/1B2F5YuERfMEfJeRXfz5oMxI8wcZLmvFJ/view?usp=sharing) |
| yolov5s          | 640        | 94.0  | 92.1   | 84.5  | [google](https://drive.google.com/file/d/1V7BMMTRk89YzoPHTw6qW3KSOwU_rlBGq/view?usp=sharing) |
| yolov7-lite-e    | 640        | 91.1  | 87.5   | 70.9  | [google](https://drive.google.com/file/d/192NLp3tu3nF7lHq62twH6Vgl_ixGfjrY/view?usp=sharing) |

### Demo

Download the model place into `weights` folder, then run:

```
python detect.py --weights weights/yolov7-tiny-face.pt --view-img
```


### Export

export to onnx and torchscript:

```
python export.py --weights weights/yolov7-tiny-face.pt
```


#### Dataset

[WiderFace](http://shuoyang1213.me/WIDERFACE/)

[yolov7-face-label](https://drive.google.com/file/d/1FsZ0ACah386yUufi0E_PVsRW_0VtZ1bd/view?usp=sharing)

#### Test

![](data/images/result.jpg)


#### Demo

* [ncnn_Android_face](https://github.com/FeiGeChuanShu/ncnn_Android_face)

#### References

* [https://github.com/deepcam-cn/yolov5-face](https://github.com/deepcam-cn/yolov5-face)

* [https://github.com/WongKinYiu/yolov7](https://github.com/WongKinYiu/yolov7)

* [https://github.com/TexasInstruments/edgeai-yolov5/tree/yolo-pose](https://github.com/TexasInstruments/edgeai-yolov5/tree/yolo-pose)

* [https://github.com/ppogg/YOLOv5-Lite](https://github.com/ppogg/YOLOv5-Lite)

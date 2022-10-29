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



<img src="https://github.com/noorkhokhar99/yolov7-face/blob/main/Screen%20Shot%201444-04-03%20at%209.54.24%20PM.png">

#### References

* [https://github.com/deepcam-cn/yolov5-face](https://github.com/deepcam-cn/yolov5-face)

* [https://github.com/WongKinYiu/yolov7](https://github.com/WongKinYiu/yolov7)

* [https://github.com/TexasInstruments/edgeai-yolov5/tree/yolo-pose](https://github.com/TexasInstruments/edgeai-yolov5/tree/yolo-pose)

* [https://github.com/ppogg/YOLOv5-Lite](https://github.com/ppogg/YOLOv5-Lite)


## Installation

```bash
git clone https://github.com/KasunThushara/yoloV5n_RPI
cd yolo5
pip install -r requirements.txt
```
## Inference with detect.py for images

```bash
python detect.py --weight yolov5n-int8.tflite --img 416 --source data/images/bus.jpg
```
## Inference with detect.py for video

```bash
python detect.py --weight yolov5n-int8.tflite --img 416 --source <your video path>
```




    
## Appendix

Any additional information goes here

https://github.com/ultralytics/yolov5

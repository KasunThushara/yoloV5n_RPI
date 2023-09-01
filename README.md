
## Installation

```bash
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
```
## Copy yolov5n-int8.tflite from this repository into yolov5 folder and paste it

## Inference with detect.py for images

```bash
python detect.py --weight yolov5n-int8.tflite --img 416 --source data/images/bus.jpg
```
## Inference with detect.py for video

```bash
python detect.py --weight yolov5n-int8.tflite --img 416 --source data/images/elephant.mp4
```

### More details can be get from

https://github.com/ultralytics/yolov5




    
## Appendix

Any additional information goes here

https://github.com/ultralytics/yolov5

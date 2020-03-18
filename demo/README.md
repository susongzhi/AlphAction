# Demo

### Installation 

To run this demo, make sure that you install all requirements following [INSTALL.md](../INSTALL.md).

### Preparation
1. Download the object detection model manually: **yolov3-spp.weights** ([Google Drive](https://drive.google.com/open?id=1T13mXnPLu8JRelwh60BRR21f2TlGWBAM)). Place it into ```data/models/detector_models```.
2. Download the person tracking model manually: **jde.uncertainty.pt** ([Google Drive](https://drive.google.com/open?id=1IJSp_t5SRlQarFClrRolQzSJ4K5xZIqm)). Place it into ```data/models/detector_models```.
3. Please download our action models. Place them into ```data/models/aia_models```. All models are available in the [Model Zoo](../README.md#model-zoo).
We also provide a practical model ([Google Drive](comming-soon...)) trained on 15 common action categories in AVA. This 
model achieves about 70 mAP on these categories.

### Usage

1. Video Input
```
cd demo
python demo.py --video-path path/to/your/video --output-path path/to/the/output 
```

2. Webcam Input
```
cd demo
python demo.py --webcam --output-path path/to/the/output
```

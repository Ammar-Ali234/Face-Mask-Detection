# Face Mask Detection using Computer Vision

![Face Mask Detection](demo_image.jpg)

## Overview

This project aims to detect whether individuals are wearing masks correctly using computer vision techniques. The model identifies faces and draws bounding boxes around them, highlighting whether a mask is present and worn properly.

## Features

- **Face Detection**: Utilizes OpenCV to detect faces in images.
- **Mask Detection**: Determines whether a detected face is wearing a mask.
- **Bounding Box Visualization**: Draws bounding boxes around detected faces and masks.
- **Easy Integration**: Implemented using YOLO, making it easy to integrate into existing projects.

## Demo $ Installation Video

Watch the demo video on [YouTube](#).

## Installation

1. Install Ultralytics:

    ```bash
    pip install ultralytics
    ```

2. Import YOLO Model:

    ```bash
    from ultralytics import YOLO
    ```

3. Train the Model:

    ```bash
    model = YOLO("yolov8n.pt")
    model.train(data="coco8.yaml", epochs=3)
    ```

## Usage

Run (get the prediction from the model) the following command to start the face mask detection:

```bash
yolo predict model=yolov8n.pt source='path_of_the_image.jpg'
```

## Acknowledgments

- Special thanks to [The Spark Foundation](https://lnkd.in/dt8nwez9) for providing the opportunity to work on this project.

## Contact

For any questions or feedback, please feel free to reach out:

- **Email**: ammaralif21@nutech.edu.pk
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/ammar-ali-a8170b297/)
- **GitHub**: [Your GitHub Profile](https://github.com/Ammar-Ali234/)
- **Youtube**: [Youtube Channel](https://www.youtube.com/channel/UCaJvDv-3_ZmCQmV2DfxXWsA)

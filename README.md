I created this repository to explore and debug a common real-world issue in computer vision: `poor object detection performance in low-light conditions`.

I began by simulating a basic object detection pipeline using a pretrained YOLOv5 model. Then, I artificially dimmed the input image to simulate low-light conditions and observed a clear drop in detection accuracy. From there, I applied `CLAHE-based preprocessing` to enhance visibility and saw a noticeable recovery in model performance.

I find that I learn **best by doing**. Not just reading. This notebook is a small reflection of how I *think* internally.

I hope this notebook captures a glimpse of the kind of hands-on thinking I’d bring to the table.

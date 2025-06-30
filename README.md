# DLW
I created this repository to explore and debug a common real-world issue in computer vision: `poor object detection performance in low-light conditions`. Although the mentorship task only required a theoretical explanation, I felt that actually building and testing a solution would help me understand the problem more deeply AND it did.

I began by simulating a basic object detection pipeline using a pretrained YOLOv5 model. Then, I artificially dimmed the input image to simulate low-light conditions and observed a clear drop in detection accuracy. From there, I applied `CLAHE-based preprocessing` to enhance visibility and saw a noticeable recovery in model performance.

While I'm still early in my AI/ML journey, I find that I learn **best by doing**. Not just reading. This notebook is a small reflection of how I *think* internally. It’s not perfect, and there’s plenty more that could be done, but the process of building this helped me think like a *mentor*: What does it fail? What’s the smallest thing I can fix? How can I help someone else see that?

I hope this notebook captures a glimpse of the kind of hands-on thinking I’d bring to DLW.

# everydayObjects_ObjectDetection

**Abstract**
The project is an application of advanced object detection models to everyday objects, specifically focusing on utensils, laptops, and drinks. The aim is to explore the capabilities of cutting-edge algorithms in accurately detecting and identifying these common items within a varied dataset. Utilizing the Computer Vision Annotation Tool (CVAT) for precise annotation, this research compares the performance, computational efficiency, and processing speed of YOLOv8 and Detectron2's Faster R-CNN models. Our findings indicate that YOLOv8 surpasses Faster R-CNN in both processing speed and detection, making it an optimal choice for real-time object detection applications. This report details the methodology employed in dataset preparation, model training, and evaluation, culminating in a critical analysis of the performance of each model under study.

**Results**
In our comparative analysis, YOLOv8 + Data Augmentation emerged as the more capable model, achieving an overall mAP50 of 75.2 % compared to Detectron2's 46.0%. Particularly noteworthy was YOLOv8's performance in laptop detection, where it reached an mAP50 of 93.5%, significantly outpacing Detectron2's 40.1%. Furthermore, YOLOv8's (with Data Augmentation) inference time was a mere 2.6ms, vastly superior to Detectron2's 66ms, and its model size of 6.23M was also substantially smaller than Detectron2's 160M. These findings underscore YOLOv8's potential for real-time application deployment, although its lower mAP50-95 score suggests room for improvement in precision at more stringent IoU thresholds.

**Future Work**
For future research, it would be beneficial increase the utensils datasets to improve the accuracy for that specific class too. Exploring advanced techniques to improve edge detection could further refine YOLOv8's capabilities. Expanding the dataset to include more instances and narrower object categories would also be crucial in providing deeper insights into the models' generalization abilities (like having a separate class for forks, spoons, etc. instead of one utensils class) and informing the development of more nuanced object detection systems.

Data - https://drive.google.com/file/d/1sKQi7YVC5bIhf8FqHUgzitOLpXbaggEO/view?usp=sharing

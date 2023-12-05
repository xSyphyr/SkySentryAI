# SkySentryAI
At SkySentryAI, our mission is to revolutionize transportation management and safety during inclement weather. We are dedicated to empowering Department of Transportation agencies with advanced AI technology to make informed, proactive decisions. Our goal is to enhance road safety, reduce accidents, and minimize traffic disruptions during adverse weather conditions. By providing real-time weather insights and predictive analysis, we enable DOTs to determine staffing needs, deploy resources strategically, and mitigate weather-related incidents effectively. We are committed to creating a safer, more efficient, and resilient transportation network for the benefit of all communities we serve.

[Google Colab](https://colab.research.google.com/drive/1K-pTGXAS7mLuoOrqYQJywbDwmwagDsav#scrollTo=MJjTOJXQY7L2)
## Logo

## Problem
Weather forecasts are not always accurate. Day in and day out there is unexpected poor weather around the world. The problem is that while there may be good weather in a town, there may be one section of a town that doesn't. We want to help Department of Transportation agencies know where and how many people to staff for a certain day. Furthermore, we want to help them redirect their staff to areas that would need the assistance more. For example an area that is foggy or rainy tends to need more assistance than where it is clear and sunny.

##  Data Deck
[Google Slide Data Deck](https://docs.google.com/presentation/d/1JuHDfsJL5S2unNAP_6iWqWC_wB_WmdSKYS6D0M1KvJ8/edit?usp=sharing)

The Data Deck above provides a comprehensive look at the diverse and carefully curated dataset instrumental in training SkySentryAI. These images capture various weather conditions and real-world scenarios, serving as the foundation for our AI models. The insights gained from this dataset empower SkySentryAI to deliver accurate and timely information, transforming how we address weather-related challenges. Dive into the slides to explore the rich tapestry of data that fuels the development of SkySentryAI's cutting-edge technology.

---

## Image Filters

---

## AlexNet
![AlexNet Image](https://miro.medium.com/v2/resize:fit:1400/1*bD_DMBtKwveuzIkQTwjKQQ.png)

AlexNet is a groundbreaking convolutional neural network (CNN) architecture that won the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) in 2012. Developed by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton, it marked a significant advance in image classification.

**Key Features:**

1. **Deep Structure:** AlexNet has eight layers, including five convolutional and three fully connected layers, challenging the belief that deep networks are hard to train.

2. **ReLU Activation:** It uses ReLU activation for faster training and to avoid the vanishing gradient problem.

3. **Normalization:** Incorporates local response normalization (LRN) in convolutional layers for better generalization.

4. **Dropout:** Employs dropout to prevent overfitting by deactivating some neurons during training.

5. **Data Augmentation:** Uses techniques like cropping and flipping during training to enhance dataset diversity.

6. **GPU Acceleration:** Utilizes GPU acceleration for faster training, making deep learning more practical for large datasets.

AlexNet's success revolutionized deep learning, influencing the design of modern CNNs used in image recognition, object detection, and more.

---

## YoloV5 Integration
In the evolution of SkySentryAI, the integration of YOLOv5 marks a significant stride in object detection and recognition within our weather analysis framework. YOLOv5, renowned for its speed and accuracy, brings a streamlined approach to identifying and tracking objects of interest in real-time.

**Key Contributions of YOLOv5 to SkySentryAI:**

1. **Efficient Object Detection:** YOLOv5's unique one-shot object detection approach facilitates rapid identification of objects within our expansive weather dataset. This efficiency is paramount in detecting and analyzing various elements, such as road conditions and potential hazards.

2. **Precision and Accuracy:** YOLOv5's advanced architecture enhances the precision and accuracy of object recognition in diverse weather scenarios. This ensures SkySentryAI delivers reliable and precise insights for effective decision-making.

3. **Adaptability to Varied Conditions:** YOLOv5's adaptability allows SkySentryAI to seamlessly navigate through diverse weather conditions, ensuring robust performance across scenarios ranging from clear skies to inclement weather.

4. **Real-time Object Tracking:** The real-time capabilities of YOLOv5 empower SkySentryAI to track and monitor objects dynamically. This is crucial for understanding the evolving weather landscape and responding proactively to potential challenges.

5. **Integration with Advanced Analytics:** YOLOv5's integration complements SkySentryAI's analytics suite, providing a comprehensive solution for not only detecting objects but also extracting valuable insights for improved decision support.

The incorporation of YOLOv5 into SkySentryAI exemplifies our commitment to leveraging state-of-the-art technologies, ensuring our platform remains at the forefront of innovation in weather analysis and prediction.

Below is a picture from the dataset that is used to train the model, ran through YoloV5. This can be used to aid in detecting broken down or abandoned vehicles on the side of the road as well as pedestrians that are in areas that they would not be.

![bad2](https://github.com/xSyphyr/SkySentryAI/assets/143010034/8a094bb7-692b-462a-a90a-7e9015dda15b)


---

## Results

---

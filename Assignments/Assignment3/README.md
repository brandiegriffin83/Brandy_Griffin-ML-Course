# Assignment 3 – Edge-Computing Video Analytics for Smart City Traffic Monitoring

## Problem
The goal of this assignment was to analyze how edge computing and video analytics can be used to improve real-time traffic monitoring in smart cities. Traditional CCTV systems collect large amounts of video data but are limited due to privacy concerns and lack of real-time processing. The problem was to evaluate how these systems can be enhanced to provide useful, real-time insights while protecting user privacy and reducing network load.

## Approach
To address this problem, I analyzed the Liverpool Smart Pedestrians project, which uses edge computing to process video data directly on local devices instead of sending raw footage to the cloud. The system uses an NVIDIA Jetson TX2 device to run deep learning models in real time.

The project applies YOLO v3 for object detection and the SORT algorithm for tracking objects such as pedestrians, vehicles, and bicycles. Instead of transmitting video, the system sends only metadata such as object counts and movement patterns. This approach reduces bandwidth usage and ensures privacy.

I also examined how the system was designed to meet real-world constraints, including limited storage, outdoor deployment conditions, and communication requirements like LoRaWAN. Performance was evaluated using datasets and real-world deployments to understand how well the system performs under different conditions.

## Results
The system achieved an average accuracy of approximately 69% and processed data at about 19.5 frames per second. While the accuracy decreased in crowded environments due to overlapping objects, the system was still able to identify overall traffic patterns effectively :contentReference[oaicite:0]{index=0}.

Real-world testing showed that the system could track thousands of objects and detect patterns such as peak traffic times and crowd movement. The use of edge computing significantly reduced network bandwidth usage while maintaining real-time performance.

## Summary
This assignment demonstrated how edge computing can transform traditional video surveillance systems into intelligent, real-time monitoring tools. It highlighted the importance of balancing accuracy, performance, and privacy in smart city applications.

Overall, this project improved my understanding of how AI, IoT, and edge computing work together to solve real-world problems. It also showed the practical challenges involved in deploying AI systems outside of controlled environments.

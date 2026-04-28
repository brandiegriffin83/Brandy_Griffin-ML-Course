# Lab 4 – IIoT Protocol Simulation (MQTT, CoAP, OPC UA)

## What I Did
For this lab, I worked on simulating multiple Industrial IoT (IIoT) communication protocols within a local development environment. I set up a project using Python and Visual Studio Code, created a virtual environment, installed required packages, and configured a Mosquitto MQTT broker. I developed and ran scripts to simulate sensor data using MQTT, created a visualization script to display real-time data, and then expanded the lab by implementing CoAP and OPC UA protocols to compare their behavior.

## What I Learned
Working through this lab gave me a deeper understanding of how different IoT communication protocols operate in real-world systems. I learned how:
- MQTT enables lightweight, publish-subscribe communication for fast data transfer  
- CoAP uses a REST-based approach that is efficient for constrained devices  
- OPC UA supports more complex, structured communication used in industrial systems  

I also gained experience setting up environments, managing dependencies, and running multiple services together. This lab helped me see how protocol choice depends on factors like performance, reliability, and system requirements :contentReference[oaicite:0]{index=0}.

## Challenges
Throughout this lab, I encountered several technical challenges that required troubleshooting. While working with MQTT, I faced a runtime issue with the visualization script that required debugging. During the CoAP setup, I ran into a port conflict (port 5683 already in use), which I had to resolve by identifying and stopping the existing process. Additionally, while working with OPC UA, I had to fix errors related to asynchronous programming (async/await usage), which required reviewing the code carefully before it would run correctly :contentReference[oaicite:1]{index=1}.

## Results
By the end of the lab, I successfully ran simulations for all three protocols. The MQTT setup produced real-time sensor data and visualizations, the CoAP client and server communicated correctly with successful responses, and the OPC UA server generated live sensor data. These results confirmed that each protocol was functioning as expected and allowed me to compare their performance and behavior in a controlled environment :contentReference[oaicite:2]{index=2}.

## Summary
This lab demonstrated how different IIoT protocols are used for different purposes in real-world applications. It reinforced the importance of selecting the right communication method based on system needs and showed how much setup, debugging, and testing is required to get these systems working correctly. Overall, this was one of the most comprehensive labs and helped strengthen my understanding of industrial AI and IoT systems.

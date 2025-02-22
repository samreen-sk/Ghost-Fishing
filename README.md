# Ghost Fishing Gear
# Idea submission for bootcamps
## Solutions Challenge 2025
![Screenshot 2025-02-14 211334](https://github.com/user-attachments/assets/90dbfd2d-de1f-49a3-ad7d-1e7ef0b0b21d)

## Team Name : Cloud Nine
## Team Members:
1. Shaik Samreen
2. Arshitha MS
3. Harini A 
4. Vedhashree G

## Problem Statement : GHOST FISHING GEAR DETECTION​
### Ghost Fishing: A Threat to Marine Life​
What if the fishing nets we left behind never stopped catching? Even years later, they continue to trap and kill marine life. Ghost fishing occurs when abandoned, lost, or discarded fishing gear keeps harming marine species, causing irreversible damage. An estimated 25,000 nets are discarded annually in the Northeast Atlantic alone, some weighing up to 10,000 pounds. These nets pollute the ocean, disrupt ecosystems, and deplete fish populations, threatening the balance of marine biodiversity. The retrieval process is dangerous, slow, and costly, leaving much of the waste uncollected.​
Ghost fishing occurs when abandoned, lost, or discarded fishing gear (ALDFG) continues to trap marine life indiscriminately. These ghost nets, often made of non-biodegradable plastics, account for 640,000 tons of marine debris annually. They harm ecosystems by:

1. Entangling and killing marine animals like turtles, dolphins, and fish.
2. Damaging coral reefs and seafloor habitats.
3. Contributing to microplastic pollution, infiltrating the food chain and threatening human health.

Studies estimate that up to 2.5% of all fishing gear is lost annually, including over 78,000 km² of nets, more than 25 million pots and traps, and 740,000 km of longlines.

![Screenshot 2025-02-15 185941](https://github.com/user-attachments/assets/85d7851f-3fa1-41a1-b113-ed81b85f2827)


Ghost fishing severely impacts marine ecosystems by continuously trapping and killing marine life long after being abandoned. Lost fishing nets, traps, and lines entangle fish, sea turtles, marine mammals, and seabirds, leading to injuries, starvation, and death. As these species decline, it disrupts the food chain, affecting predator-prey relationships and overall biodiversity. Additionally, ghost gear damages coral reefs and seagrass beds, which serve as essential habitats for many marine organisms. Over time, the decomposition of synthetic materials in ghost nets releases microplastics into the ocean, further polluting the marine environment. This ongoing destruction threatens fish populations, disrupts coastal economies, and accelerates oceanic degradation, making ghost fishing a critical environmental concern.

This issue directly aligns with UN Sustainable Development Goal 14: Life Below Water, which aims to conserve and sustainably use oceans, seas, and marine resources. Ghost fishing undermines efforts to reduce marine pollution, restore ecosystems, and promote sustainable fisheries.

## Proposed Solution:
### App Name : EcoNet
![Screenshot 2025-02-15 185749](https://github.com/user-attachments/assets/36aa34ef-411c-49be-a869-0f20665d04a1)


We propose EcoNet, a mobile application that leverages AI-powered satellite data to detect ghost gear hotspots in real time. By combining Google Earth Engine, AI/ML models, and Firebase, EcoNet provides real-time detection, visualization, and task allocation to volunteers and NGOs, ensuring faster response and marine ecosystem restoration.​The app visualizes these hotspots through interactive heatmaps, enabling better decision-making. Real-time alerts notify NGOs, volunteers, and fishermen, ensuring quick response and cleanup efforts. A task-claiming system allows users to take ownership of cleanup operations, promoting coordinated action. By integrating technology with community-driven efforts, EcoNet provides an efficient, scalable solution to combat ghost fishing and restore marine ecosystems.​

### List of features offered by the solution​:

1. AI-Powered Ghost Gear Detection : Uses Google Earth Engine and ML models to identify ghost fishing gear from satellite imagery.​
3. Real-Time Heatmap Visualization : Displays ghost gear hotspots using Google Maps API for easy tracking.​
4. Task Allocation & Cleanup Management : Volunteers & NGOs can claim cleanup tasks and update progress within the app.​
5. Automated Alerts & Notifications : Firebase Cloud Messaging sends real-time alerts to nearby responders.​
6. AI-Generated Impact Reports : Uses Gemini AI to generate reports on cleanup efforts (marine life saved, area cleaned).​
7. Gamification & Engagement : Leaderboards, badges, and rewards to motivate participation.​

### Process flow diagram or Use-case diagram

![Screenshot 2025-02-14 234000](https://github.com/user-attachments/assets/bc0806d0-483c-4ca3-9667-0a08bd745b19)

The provided diagram is a Use-Case Diagram that illustrates the interaction between users, external systems, and the core functionalities of the Econet AI-powered Ghost Net Removal Network. It depicts how users can detect ghost nets, visualize their locations through heat maps, and identify the type of net using AI-powered tools like Gemini AI, Google Earth Engine API, and Google Maps API. Once a ghost net is detected, a cleanup notification is sent, allowing users to accept tasks, remove ghost nets, and upload proof of cleanup. Sponsors play a crucial role by providing rewards and funding to incentivize cleanup efforts, while the application maintains a leaderboard to track contributions. The diagram effectively showcases the structured workflow of the app, emphasizing the role of AI, user engagement, and sponsorship in tackling ghost fishing gear pollution.This diagram effectively outlines the Econet app's core functionality and stakeholder interactions.

### Architecture diagram of the proposed solution​:

![Architecture](https://github.com/user-attachments/assets/0f546097-974b-45d9-a3a6-e3eb39127fd3)


The provided Architecture Diagram outlines the workflow of the proposed ghost fishing gear detection and cleanup solution, detailing the key stages from detection to impact analysis. The process begins with data collection and ghost net detection, utilizing AI, image recognition, or crowdsourced reporting. Once detected, a notification and response system alerts users or cleanup organizations to take action. The cleanup and verification stage ensures the proper removal of ghost nets, followed by a reward system that incentivizes participants for their efforts. The system then incorporates tracking and analytics to monitor progress and measure the impact of cleanups. Finally, visualization and insights provide data-driven reports, heat maps, and trends to enhance future detection and cleanup strategies. This structured architecture ensures an efficient, technology-driven approach to combating ghost fishing while promoting sustainability and community engagement.

### Technologies that are being used:
#### AI/ML & Data Processing​ :
   1. Google Earth Engine API – Access satellite imagery for ghost gear detection.​
   2. TensorFlow/PyTorch – Train and deploy ML models for detecting ghost nets.​
   3. Google Cloud AI – Host and run AI models for real-time predictions.​
#### Frontend Development​:
   1. Flutter – Cross-platform mobile app development (iOS & Android).​
   2. Google Maps API– Display ghost gear hotspots on an interactive heatmap.​
#### Backend & Cloud Services​:
  1. Firebase Firestore – Store and manage hotspot data in real-time.​
  2. Google Cloud Functions – Handle task creation, assignment, and processing.​
  3. Firebase Cloud Messaging – Send real-time notifications to NGOs/volunteers.
#### AI-Powered Insights & Visualization​:
  1.Gemini AI APIs – Generate automated impact reports from cleanup data.​
  2.Chart.js / D3.js – Visualize cleanup progress with interactive charts and stats.​
#### Deployment & Hosting​:
  1. Google Cloud Platform (GCP) – Host backend services, ML models, and APIs.​
  2. Firebase Hosting – Deploy static assets and integrate services.​


### Future Development:
#### IOT Smart Buoys:
Deploy IoT-enabled devices in high-risk zones to detect ghost nets using sonar and underwater cameras.​
#### Global Dataset Contribution:​
​Collaborate with environmental organizations to create a comprehensive database of ghost gear locations​.
#### Advanced AI Models:​
​Enhance AI models with larger datasets for higher accuracy and efficiency.​
#### Community Engagement:​
​Allow fishermen and coastal communities to report sightings directly via the app.​



​Addressing the issue of ghost fishing gear is crucial to achieving Sustainable Development Goal (SDG) 14: Life Below Water, which aims to conserve and sustainably use the oceans, seas, and marine resources. The solutions discussed and proposed collaboration between governments, fisheries, conservation organizations, and local communities is essential for implementing effective policies and cleanup efforts. Moreover, raising awareness among fishers and the general public about the long-term consequences of ghost gear will encourage more sustainable fishing practices. 


By taking proactive measures and leveraging technological innovations, we can protect marine biodiversity, support coastal economies, and contribute to a healthier ocean ecosystem. Sustainable fishing practices and responsible waste management are key steps toward mitigating this global issue and ensuring a sustainable future for marine life and humanity alike.

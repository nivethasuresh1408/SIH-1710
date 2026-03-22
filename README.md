# Smart India Hackathon Workshop
# Date:22-03-2026
## Register Number:212223040137
## Name:NIVETHA S
0-## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea
1.3D Indoor Navigation Maps

Interactive 3D maps of station layouts with real-time navigation and platform guidance.

2.Multi-Platform Access

Available via mobile app and touch-enabled digital kiosks placed throughout the station.

3.Accessibility Support

Voice-guided navigation, screen reader compatibility, and routes optimized for wheelchair users.

4.Real-Time Updates

Instant updates on platform changes, facility closures, and train arrival/departure information.

5.Integrated Passenger Experience

Seamless integration with existing railway apps (e.g., IRCTC) using PNR to guide passengers from entry to coach.


## Proposed Solution / Architecture Diagram
![2025-04-30 (8)](https://github.com/user-attachments/assets/eb3f1e90-e34f-4a2f-8c44-353bc6dee1ec)

## Use Cases
![Screenshot 2025-04-30 114819](https://github.com/user-attachments/assets/c14d664a-db6d-440e-840b-90cbcc6752d6)



## Technology Stack
👨‍💻 Front-End
React Native – Cross-platform mobile app (Android/iOS)

HTML5 / CSS3 / JavaScript – For digital kiosk interface

Three.js / Mapbox GL – For 3D interactive station maps

🧠 Back-End
Node.js – RESTful APIs for data handling and integration

Express.js – Lightweight server framework

Socket.IO – For real-time updates (e.g., platform changes)

🗺️ Navigation & Mapping
IndoorAtlas / Mapwize / Google Indoor Maps – Indoor positioning and routing

GeoJSON – Station layout and facility location data format

🔗 Integration & Data
IRCTC / NTES API – Train timings and PNR integration

Firebase / MongoDB – Real-time database for user activity and facility updates

♿ Accessibility Tools
Text-to-Speech APIs – Voice guidance

ARIA (Accessible Rich Internet Applications) – Screen reader support

☁️ Cloud & DevOps
AWS / Azure / Firebase Hosting – App hosting and scaling

GitHub / GitLab – Version control and collaboration

Postman / Swagger – API testing and documentation


## Dependencies
react-native-maps – Map rendering and navigation

react-navigation – Screen and route management

axios – API calls to backend/server

expo-location – User location tracking

react-native-tts – Text-to-speech for voice guidance

@react-native-community/geolocation – Real-time location access



# Smart India Hackathon Workshop

# Date: 18-03-2026
## Register Number: 212223220112
## Name: Suchitra Nath

## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations

## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea

We propose a system called RailNav AI, a smart railway navigation assistant that combines:

* Mobile application for personal navigation
* Smart kiosks inside stations
* Indoor positioning system (BLE/WiFi-based)
* Voice-guided assistance for visually impaired users

The system will provide:

* Real-time user location inside station
* Shortest path navigation
* Voice + visual guidance
* Accessibility-based routing (ramps, lifts)

## Proposed Solution / Architecture Diagram

<img width="439" height="347" alt="image" src="https://github.com/user-attachments/assets/e6d43c84-a52a-4eb2-8e4a-a7ca47f8b1e3" />

Mobile App/Kiosk → User interface
API Gateway → Handles requests
Routing Engine → Calculates shortest path
Database → Stores station layout
IPS → Tracks user location in real-time

## Use Cases

<img width="280" height="95" alt="image" src="https://github.com/user-attachments/assets/bba01de5-34ed-4279-a0fd-7df320d36162" />

# Detailed Use Cases:

1.Search Facility
* User enters "Platform 5" or "Restroom"
* System shows location on map

2.Get Navigation
* System calculates shortest route
* Displays step-by-step directions

3.Voice Assistance
* User speaks destination
* System gives audio directions

4.Accessibility Mode
* Suggests wheelchair-friendly paths
* Avoids stairs

5.Real-time Updates
* Re-routes if user deviates
* Updates based on crowd density

## Technology Stack

| Layer              | Technology                        |
| ------------------ | --------------------------------- |
| Frontend           | React Native / Flutter            |
| Backend            | Flask / Node.js                   |
| Database           | PostgreSQL / MongoDB              |
| Graph Processing   | NetworkX                          |
| Maps               | Three.js (3D visualization)       |
| Indoor Positioning | BLE Beacons / WiFi                |
| AI/ML              | Python (for routing & prediction) |
| APIs               | Indian Railways API               |

## Dependencies

🔹 Software Dependencies

Node.js / Python
Flask / Express.js
React Native / Flutter
PostgreSQL / MongoDB
Three.js

🔹 Hardware Dependencies

Bluetooth Low Energy (BLE) Beacons
WiFi routers for triangulation
Touchscreen kiosks

🔹 Libraries

NetworkX (graph routing)
SpeechRecognition (voice input)
Text-to-Speech (audio output)
Map rendering libraries

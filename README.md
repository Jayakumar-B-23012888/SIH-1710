# Smart India Hackathon Workshop
# Date: 18-09-2026
## Register Number: 212223040073
## Name: JAYAKUMAR B

## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations

## Problem Description
Railway stations are complex environments with many facilities such as ticket counters, platforms, restrooms, food courts, waiting areas, lifts, escalators, entrances and exits. Passengers may face difficulties in finding the required location, especially in large or unfamiliar railway stations.

The proposed system is a smart railway station navigation platform that helps passengers locate facilities and destinations within the station. It provides interactive maps, real-time directions, accessibility support and railway information through mobile applications and digital kiosks.

The system provides:
- Interactive 2D/3D station maps
- Step-by-step navigation
- Facility search
- Voice-guided navigation
- Wheelchair-friendly routes
- Digital kiosk support
- Real-time facility and railway updates
- Train and platform information
- Regular station map updates
- Integration with railway services

The main objective is to reduce confusion, save passenger time and make railway station navigation more accessible and convenient.

## Problem Creater's Organization
Ministry of Railway

## Idea
The idea is to develop a Smart Railway Station Navigation System that allows passengers to easily find facilities and navigate inside railway stations using a mobile application or digital kiosk.

1. Interactive Station Map
The system provides interactive 2D/3D maps showing platforms, ticket counters, restrooms, food courts, waiting areas, lifts, escalators, entrances and exits.

2. Facility Search
Passengers can search for facilities such as toilets, ticket counters, food courts, platforms and waiting halls. The system displays the location of the selected facility.

3. Smart Navigation
The system provides step-by-step directions from the user's current location to the selected destination.

4. Accessibility Support
The system provides wheelchair-friendly routes and gives preference to lifts and ramps. Voice guidance is provided for visually impaired passengers.

5. Digital Kiosk
Touch-screen kiosks installed inside railway stations allow passengers to search for facilities and obtain directions.

6. Real-Time Updates
The system provides updated information about facilities, platforms, trains and service changes.

7. Admin Portal
Railway administrators can update station layouts, facility locations and other navigation information.

## Proposed Solution / Architecture Diagram

<img width="1379" height="492" alt="image" src="https://github.com/user-attachments/assets/9a2a34d5-269e-4ddd-9756-cc61fc2ebf63" />


The proposed architecture consists of the following components:

1. Passenger Mobile Application
2. Digital Kiosk
3. Authentication System
4. API Gateway / Backend
5. Station Map Service
6. Route Engine
7. Accessibility Engine
8. Real-Time Update Service
9. Notification Service
10. PostgreSQL / PostGIS Database
11. Admin Portal
12. Railway / Train APIs

The mobile application and digital kiosk communicate with the backend through APIs. The backend retrieves station map data and railway information from the database and external railway APIs. The route engine calculates navigation paths, while the accessibility engine provides suitable routes for passengers with disabilities.

## Use Cases

<img width="1382" height="435" alt="image" src="https://github.com/user-attachments/assets/a53e1d98-93ff-4128-9056-9d850d00340b" />


1. Passenger
- Login
- Search for facilities
- View interactive station map
- Get navigation directions
- View train and platform information
- Check facility status
- Report incorrect locations

2. Visually Impaired Passenger
- Use voice-guided navigation
- Receive audio directions
- Search for accessible facilities

3. Wheelchair User
- Search for accessible facilities
- Get wheelchair-friendly routes
- Use lifts and ramps
- Avoid stairs and inaccessible paths

4. Station Administrator
- Update station layout
- Add or modify facilities
- Manage points of interest
- Correct incorrect location information

5. Railway Service / API
- Provide train information
- Provide platform information
- Provide railway service updates

## Technology Stack

React.js

Node.js

Express.js

PostgreSQL

PostGIS

Google Maps API / Mapping Service

Firebase Authentication

HTML5

CSS3

JavaScript

Web Speech API

Git

GitHub

Postman / Insomnia

## Dependencies

1. Station map and floor-plan data

2. Facility and point-of-interest data

3. Mapping and routing service

4. Railway API for train and platform information

5. PostgreSQL/PostGIS database

6. Authentication service

7. Internet/network connectivity

8. Digital kiosk hardware

9. Backend hosting and database hosting

10. Data collection and regular station information updates

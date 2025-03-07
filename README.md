# WanderSync: A Collaborative Travel Management System

## Project Overview
WanderSync is a collaborative travel management system developed as part of the CS 2340 course. The application enables users to plan and manage trips collaboratively in real-time, providing a seamless experience for group travel planning.

## Key Features
- **Secure Account Creation**
  - User authentication and authorization
  - Secure data handling
  - Profile management

- **Itinerary Management**
  - Add and edit travel plans
  - Manage destinations and dates
  - Track accommodations
  - Plan activities
  - Organize trip details

- **Real-Time Collaboration**
  - Simultaneous trip editing
  - Live updates for all participants
  - Shared itinerary viewing
  - Collaborative decision making

- **Firebase Integration**
  - Real-time data synchronization
  - Secure data storage
  - User authentication
  - Cloud Firestore database

## Technical Architecture

### Fragments
1. **DestinationFragment**
   - Displays destinations in 'location, start_date, end_date' format
   - Manages destination-related interactions

2. **DiningEstablishmentsFragment**
   - Handles restaurant reservations
   - Displays dining options and availability

3. **AccommodationsFragment**
   - Shows accommodation details
   - Manages room information and bookings

### Design Patterns & Principles
- **Singleton Pattern**
  - Used for managing shared resources
  - Ensures single instance for critical components

- **SOLID Principles**
  - Single Responsibility Principle
  - Open/Closed Principle
  - Liskov Substitution Principle
  - Interface Segregation Principle
  - Dependency Inversion Principle

## Testing
- Minimum two unit tests per team member
- Coverage for Sprint 1 and 2 functionalities
- JUnit testing framework implementation

## Technical Requirements
- Android Studio
- Java Development Kit (JDK)
- Firebase Account
- Minimum Android SDK version: [Version]

## Setup Instructions
1. Clone the repository
2. Open project in Android Studio
3. Configure Firebase:
   - Add google-services.json
   - Enable Authentication
   - Set up Firestore
4. Build and run the project

## Team Members
- [Team Member 1]
- [Team Member 2]
- [Team Member 3]
- [Team Member 4]

## Project Status
Current Sprint: [Sprint Number]

## License
[License Information]

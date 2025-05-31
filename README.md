# 🌿 Saudi Eco Tour

A mobile application promoting eco-tourism in Saudi Arabia, developed as a graduation project at Princess Nourah Bint Abdulrahman University.

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)](https://firebase.google.com)
[![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)](https://developers.google.com/maps)

> **Note:** This repository showcases the design and functionality of our graduation project. The application was successfully developed and presented as part of our Computer Science degree requirements.

## 📱 Project Overview

Saudi Eco Tour is a comprehensive mobile application designed to promote sustainable tourism in Saudi Arabia, supporting Vision 2030 initiatives. The app connects travelers with the country's rich natural and historical heritage while encouraging eco-friendly exploration.

### 🎯 Key Features

- **🗺️ Interactive Exploration** - Discover natural and historical sites across Saudi Arabia
- **⭐ Community Reviews** - Read and share authentic travel experiences  
- **📍 Smart Navigation** - Integrated maps with detailed location information
- **➕ User Contributions** - Submit new places and events to expand the database
- **🌱 Eco-Friendly Focus** - Promote sustainable tourism aligned with Vision 2030
- **📱 Intuitive Design** - User-friendly interface optimized for mobile experience

## 🎓 Academic Information

**Institution:** Princess Nourah Bint Abdulrahman University  
**Faculty:** Computer and Information Science  
**Course:** Graduation Project 2 — Computer Science  
**Academic Year:** 2024  
**Project Status:** ✅ Successfully Completed & Presented

### 👥 Development Team

| Name | Role |
|------|------|
| **Rajawi Alqhtani** | Project Lead |
| Ruba Mohameed Alyouseef | Developer |
| Rawan Saif Aldosery | Developer |
| Afnan Saad Alotaibi | Developer |
| Ebtehal Almohaimeed | Developer |

**Academic Supervisors:**  
👩‍🏫 Dr. Faten Ben Hmida  
👩‍🏫 Dr. Wided Chaari

## 🛠️ Technology Stack

- **Frontend:** Flutter (Dart)
- **Backend Services:** Firebase
  - Authentication System
  - Cloud Firestore Database
  - Cloud Storage
- **Maps & Location:** Google Maps API
- **Development Environment:** Android Studio, VS Code

## 🏗️ System Architecture

Our application implements a **Multi-Layer Architecture** pattern, chosen for its flexibility, security, and maintainability benefits. This architectural approach provides clear separation of concerns between different system components.

### Architecture Benefits

- **🔧 Flexibility** - Clean separation between data, processing, and presentation layers
- **🔒 Enhanced Security** - Isolation between components reduces system vulnerabilities  
- **🎯 Clear Responsibility** - Each layer has distinct, well-defined responsibilities
- **📈 Scalability** - Independent layer management enables easier system scaling

### Layer Structure

#### 1. **📱 Presentation Layer**
- **Purpose:** User Interface and User Experience
- **Components:** Flutter widgets, screens, and UI components
- **Responsibility:** 
  - Display content to end users through intuitive GUI
  - Handle user interactions and input validation
  - Provide responsive design across different device sizes

#### 2. **⚙️ Business/Domain Layer** 
- **Purpose:** Business Logic and Rules Implementation
- **Components:** Service classes, business rule validators, workflow managers
- **Responsibility:**
  - Execute specific business rules for eco-tourism operations
  - Process user requests and apply domain-specific logic
  - Independent of data presentation and storage concerns

#### 3. **🔗 Persistence/Data Access Layer**
- **Purpose:** Data Access Management
- **Components:** Data Access Objects (DAO), Firebase service wrappers
- **Responsibility:**
  - Provide abstraction for data operations
  - Handle Object-Relational Mapping (ORM) equivalent operations
  - Manage data access patterns and caching strategies

#### 4. **🗄️ Database Layer**
- **Purpose:** Data Storage and Retrieval
- **Components:** Firebase Firestore, Cloud Storage
- **Responsibility:**
  - Store and retrieve application data
  - Maintain data integrity and consistency
  - Handle data persistence without additional processing

## 📸 Application Showcase

### System Architecture
![System Architecture](https://github.com/user-attachments/assets/5c224217-2b20-48eb-9ac9-066d7b9969b3)
*Multi-layer architecture design showcasing the app's technical foundation*

### Authentication & User Onboarding
<div align="center">
  <img src="https://github.com/user-attachments/assets/7115df4c-6e0e-4930-9a7e-d69230216282" alt="Welcome & Login" width="250"/>
  <img src="https://github.com/user-attachments/assets/65d8a720-4d37-44da-99bb-8465bc111cfd" alt="Registration & Activation" width="250"/>
  <img src="https://github.com/user-attachments/assets/acfa2afd-beac-45eb-95bd-1f8ab67b0276" alt="Sign-In & Homepage" width="250"/>
</div>

*Splash screen, user registration, account activation, and main dashboard*

### Place Discovery & Navigation
<div align="center">
  <img src="https://github.com/user-attachments/assets/dda5e8f1-fc29-46ef-abd8-ec741d51aa82" alt="Top Places & Details" width="250"/>
  <img src="https://github.com/user-attachments/assets/4cf2a285-bf94-44bf-8936-e5d5cfe9c434" alt="Map & Categories" width="250"/>
  <img src="https://github.com/user-attachments/assets/735c8300-96e4-4ae5-ba30-1ed4818fcb05" alt="Events & Categories" width="250"/>
</div>

*Browse top-rated destinations, interactive maps, category filtering, and local events*

### User Engagement & Support
<div align="center">
  <img src="https://github.com/user-attachments/assets/5c928632-c433-4ea5-aa08-ee0e50762765" alt="Feedback System" width="250"/>
  <img src="https://github.com/user-attachments/assets/be572263-d352-442a-ab1a-5d8383a2a144" alt="Support & Account" width="250"/>
  <img src="https://github.com/user-attachments/assets/7f0c4a85-25d2-4cb8-bbb7-9ede51393c5e" alt="Profile & Add Place" width="250"/>
</div>

*Feedback submission, customer support, account management, and place contribution*

### Content Management System
![Place Submission Workflow](https://github.com/user-attachments/assets/2c8f1c0f-db79-4f9c-a161-71d25b947f81)
*Complete workflow for users to submit and manage new tourist destinations*

## 🌍 Vision 2030 Impact

This project directly contributes to Saudi Arabia's Vision 2030 by:

- **🏛️ Heritage Preservation** - Showcasing Saudi Arabia's cultural and natural landmarks
- **💚 Environmental Sustainability** - Promoting eco-friendly tourism practices
- **📈 Economic Growth** - Supporting domestic tourism development
- **💻 Digital Innovation** - Leveraging technology for enhanced user experiences
- **🤝 Community Participation** - Enabling citizens to contribute to tourism promotion

## 🏆 Project Achievements

- ✅ **Successfully Designed & Developed** a fully functional mobile application
- ✅ **Comprehensive System Architecture** with multi-layer design approach
- ✅ **User-Centered Design** with intuitive interface and smooth user experience
- ✅ **Integration of Modern Technologies** including Flutter, Firebase, and Google Maps
- ✅ **Academic Excellence** - Met all graduation project requirements
- ✅ **Real-World Application** - Addresses actual tourism challenges in Saudi Arabia

## 📋 Project Features Demonstrated

### Core Functionality
- User authentication and profile management
- Interactive map integration with location services
- Place discovery with ratings and reviews
- Category-based filtering and search
- Event listings and details
- User-generated content submission
- Feedback and suggestion system
- Help center and customer support

### Technical Implementation
- Clean, scalable architecture design
- Responsive mobile interface
- Real-time database integration
- Secure user authentication
- Cloud storage for multimedia content
- API integration for mapping services

## 🎯 Learning Outcomes

Through this project, our team gained expertise in:
- **Mobile App Development** using Flutter framework
- **Backend Services** integration with Firebase
- **UI/UX Design** principles for mobile applications
- **Project Management** and collaborative development
- **Academic Research** and technical documentation
- **Presentation Skills** for project defense

## 📊 Project Documentation

This project includes comprehensive documentation covering:
- System requirements analysis
- Technical architecture design
- User interface mockups and prototypes
- Database schema and design
- Testing procedures and results
- User manual and technical specifications

## 🙏 Acknowledgments

- **Princess Nourah Bint Abdulrahman University** for providing excellent academic resources
- **Dr. Faten Ben Hmida** and **Dr. Wided Chaari** for their invaluable guidance and mentorship
- **Faculty of Computer and Information Science** for the comprehensive curriculum
- **Saudi Tourism Authority** for inspiration and cultural insights
- **Flutter and Firebase communities** for extensive documentation and support

## 📞 Contact Information

**Project Team Lead:** Rajawi Alqhtani  
**Institution:** Princess Nourah Bint Abdulrahman University  
**Faculty:** Computer and Information Science  
**Program:** Bachelor of Computer Science

---

<div align="center">
  <p><strong>🎓 Academic Excellence in Mobile App Development</strong></p>
  <p><strong>🇸🇦 Proudly Supporting Saudi Arabia's Vision 2030</strong></p>
  <p><em>Developed with dedication by PNU Computer Science Students</em></p>
</div>

# Title of the project -> 
## FoodLoop: AI-Powered Hyperlocal Application for Optimized Food Redistribution and Community Hunger Mitigation.

## Introduction ->
- AI-powered chatbot connecting food donors, NGOs, and recipients. 
- Uses AI and location data for smart food redistribution.
- Enables real-time chat-based coordination for food collection and delivery.
- Promotes sustainability and supports the Zero Hunger goal.


## Problem statement of the project ->
- Large amounts of edible food are wasted daily while many people still face hunger. 
- There is no efficient, real-time system to connect food donors with nearby recipients or NGOs.
- Manual coordination leads to delays, food spoilage, and poor redistribution efficiency.
- A smart, automated solution is needed to optimize food collection and reduce hunger at the community level.

## Purpose of the project ->
### Why FoodLoop?
- The purpose of the FoodLoop project is to leverage Artificial Intelligence application technology to develop an automated food redistribution system. 
- It aims to connect food donors, NGOs, and recipients in real time to minimize food wastage and community hunger. 
- The system uses machine learning and geolocation intelligence to efficiently match surplus food with nearby needy communities.
- The project aims to achieve the following objectives :
  - Minimize food wastage through efficient redistribution
  - Enhance coordination and speed between donors and recipients.
  - Support sustainability goals like Zero Hunger (SDG 2).

## Methodology for the Project ->
1. User Registration & Authentication
2. Food Listing & Availability
3. Smart Matching System
4. Real-Time Notifications & Tracking
5. Data Analytics & Insights
6. Feedback & Verification System
7. sustainability Integration


## Architectue flow of Foodloop ->

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/c1459df1-c223-4cc2-98a8-a4ecb7133f22" />


## Algorithm used in Foodloop for donar matching ->
### AI-Based Smart Matching Algorithm:
- A K-Nearest Neighbors (KNN) based Smart Matching Algorithm for optimally connecting surplus food with the most suitable nearby NGOs and recipients. The model compares each new food listing with past successful matches by analyzing donor-side information (food type, quantity, freshness, time of listing) and recipient-side needs (location, urgency, demand pattern). Hence, it is expected to give better matching performance than simple rule-based or manual decision methods.
- Example: Food listings are matched with recipients using similarity — i.e., if past NGOs that accepted fresh cooked meals were located within 3–5 km and marked high urgency, then KNN identifies similar NGOs nearby and recommends the closest and most relevant match for immediate pickup.

## Hardware & Software requirements ->

### Hardware Requirements :
- Smartphone: Android device with camera (720p or higher)
- GPS: Device must support location services for donors, NGOs, and volunteers
- RAM: Minimum 2GB for smooth app performance
- Processor: Dual-core or higher
- Desktop/Laptop: Optional for NGO/Admin dashboards
- Network: Stable internet for real-time notifications and live tracking

### Software Requirements :
- Frontend: React.js, Tailwind CSS, Fetch for API calls
- Backend: Node.js, Express.js
- Database: cloud-based NoSQL
- Browser Support: Chrome, Edge, Android WebView
- OS Support: Android 8+, Windows 10+

## Code Structure of FoodLoop ->

Frontend/ (React)
|─ src/
│  ├─ pages/
│  │  ├─ Home.jsx
│  │  ├─ OnboardingRole.jsx
│  │  ├─ DonorDashboard.jsx
│  │  ├─ AddListing.jsx
│  │  ├─ RecipientDashboard.jsx
│  │  ├─ MyMatches.jsx
│  │  ├─ ListingDetail.jsx
│  │  ├─ Notifications.jsx
│  │  └─ AdminDashboard.jsx
│  ├─ components/
│  ├─ services/
│  ├─ hooks/
│  └─ Layout.js
└─ package.json
 Backend/ (Node.js / Serverless (API + jobs))
├─ routes/
├─ controllers/
├─ models/
├─ services/
├─ jobs/
└─ server.js


## Output of Foodloop ->
### Login page of foodloop:
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/952dd5db-6219-43d9-a99e-0452e7dc8d3a" />

### Add surplus page of foodloop:
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/6a645268-4e3d-4f58-842e-0b0d8222810d" />


## Conclusion for Foodloop -> 
- FoodLoop uses AI and geolocation to connect donors, NGOs, and recipients for efficient food redistribution.
- It helps reduce food wastage and mitigate hunger through real-time, automated coordination. 
- The project supports sustainability goals and promotes a smarter, hunger-free community.
- Overall, FoodLoop represents a step toward creating a smarter, more compassionate, and waste-free society through technology-driven social innovation.

## References for the project ->

1. https://pubs.aip.org/aip/acp/article-abstract/3325/1/040020/3366028/Ending-hunger-saving-food-Innovations-for-surplus.

2. K. F. Victor and I. Z. Michael, “Intelligent data analysis and machine learning: Are they really equivalent Concepts?,” in 2017 Second Russia and Pacific Conference on Computer Technology and Applications (RPC), 2017, pp. 59–63.

3. Kumar, R., Singh, A., & Patel, M. (2025). Enhancing Food Sustainability Through Technological Innovation: A Paradigmatic Approach to Minimizing Household Food Wastage via an AI-Enabled Application. Journal of Environmental Informatics & Smart Technology, 8(2), 2025.

4. Saleth, E., Balaji, S., Yashema, N., & Akshaya, D. (2025). Zero Impact AI-Driven Food Redistribution System for Sustainable Waste Reduction. International Journal for Research Trends & Innovation, 10(4), April 2025.

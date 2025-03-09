
# Define 3.0
The official template repository for Define 3.0

![DefineHack 2025 Logo](https://github.com/user-attachments/assets/8173bc16-418e-4912-b500-c6427e4ba4b6)



# VedAlert 
 ![Your Gateway to Real-Time Alerts and Insights](https://raw.githubusercontent.com/adi0213/BeyondBytes/refs/heads/main/DALL%C2%B7E%202025-03-09%2008.55.34%20-%20An%20overview%20map%20style%20image%20connecting%20various%20Ayush%20centers%20with%20routes%2C%20similar%20to%20a%20Google%20Maps%20view.%20Include%20several%20marked%20locations%20along%20the%20ro.webp)

### Team Information
- **Team Name**: BeyondBytes 
- **Track**: AI in Traditional Medicine (AYUSH)

### Team Members
| Name | Role | GitHub | LinkedIn |
|------|------|--------|----------|
| Ziya  | Team Lead | [@ziyamoosir](https://github.com/ziyamoosir) | [Ziya](https://www.linkedin.com/in/ziya-m-a950152bb/) |
| Adith S | Developer | [@adi0213](https://github.com/adi0213) | [Profile](https://linkedin.com/in/username) |
| Praful CJ | Developer | [@prafulcj2015](https://github.com/prafulcj2015 ) | [Profile](https://linkedin.com/in/username) |
| Ramgovind | Presentation and Strategy Lead | [@ramgoviind](https://github.com/ramgoviind) | [Ramgovind](https://www.linkedin.com/in/ram-govind-7968892a2/) |

## Project Details

### Overview
We are developing an AI-powered Disease Alert System that analyzes Google Trends data to predict potential disease outbreaks in real-time. The system features a specialized AI chatbot, trained exclusively on AYUSH knowledge, to provide accurate traditional medicine recommendations and answer user queries. By integrating AI-driven predictions, it enhances early awareness and prevention, promoting a sustainable, data-backed approach to public health.

### Problem Statement
How can AI be used to predict outbreaks and connect people with nearby AYUSH centers and relevant traditional remedies, ensuring timely action before diseases spread further?

### Solution
We are building an AI-powered Disease Alert System that detects and verifies outbreaks using real-time data from user reports, health sources, and trends. The system sends instant alerts, displays disease hotspots on an interactive map, and provides scientifically validated AYUSH remedies tailored to detected outbreaks. Users can report symptoms, receive location-based alerts, and access nearby AYUSH centers for expert consultation. Integrated as both a mobile app and Telegram bot, our solution ensures early intervention, prevents misinformation, and promotes holistic healthcare using AI-driven insights.

### Demo
[![Project Demo](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)
_Replace VIDEO_ID with your YouTube video ID or provide an alternative demo link_

### Live Project
[VedAlert](t.me/VedAlertBot)
[Prototype](https://www.figma.com/proto/IF99NJv2WkH979Xzt7bOBt/VedAlert-Prototype?page-id=403%3A2894&node-id=518-10&p=f&viewport=-237%2C-1189%2C0.63&t=3TRzjC88Y6NStKvw-1&scaling=contain&content-scaling=fixed&starting-point-node-id=518%3A10)

## Technical Implementation

### Technologies Used
- **Frontend**: Python,Figma,html,css
- **Backend**: Python,node.js
- **Database**: Sqlite
- **APIs**: Telegram,geopy,bs4,pytrends,generative ai,mapbox
- **DevOps**: Github
- **Other Tools**: [Technologies]

### Key Features
- Ai based Disease Alert and Prediction
- Real-Time Disease Detection & Verification
- AYUSH-Based Preventive & Curative Remedies
- Personalized Ayush AI chatbot
- Symptom Reporting & AI Analysis
- Personalized & Hyper-Localized Alerts Based on GPS Location

## Setup Instructions

### Prerequisites
- Requirement 1
- Requirement 2
- Requirement 3

### Installation 
```bash
pip install requests
pip install pandas
pip install pytrends
pip install python-telegram-bot
pip install geopy
pip install beautifulsoup4
pip install google-generativeai
pip install aiohttp
```

### Running the Project
```bash
t.me/VedAlertBot
```

## Additional Resources

### Project Timeline
_Brief overview of your development process and milestones_

### Challenges Faced
Challenges Encountered & Solutions Adopted in the AYUSH Telegram Bot

Lack of Official Datasets

Challenge: There were no official datasets to train an AI model for AYUSH-based query answering.
Solution: We used data from research papers, government health portals, and user-created FAQs to create a bespoke dataset.
Trends API Limitations

Challenge: The API limited the number of cross-references at a time, hindering response times.
Solution: We made API calls more efficient by introducing caching techniques and giving priority to high-relevance queries to optimize efficiency.
Google Maps API Access Issues

Challenge: No access to Google Maps API forced us to implement Mapbox, which reduced the ease of AYUSH clinic query.
Solution: We created a workaround by using open-source location databases and providing users with the facility to manually filter search results.
Manual Interaction Requirement

Challenge: The bot had to be manually triggered since automatic updates could only be done every X hours, rendering real-time detection of disease outbreaks impossible.
Solution: We shifted to disease outbreak prediction through the analysis of historical trends, user reports, and other data sources for early warning.

### Future Enhancements
_Share your vision for future development_

### References (if any)
- [Reference 1](link)
- [Reference 2](link)

---

### Submission Checklist
- [✅] Completed all sections of this README
- [✅] Added project demo video
- [✅] Provided live project link
- [✅] Ensured all team members are listed
- [✅] Included setup instructions
- [✅] Submitted final code to repository

---

© Define 3.0 | [Define 3.0](https://www.define3.xyz/)

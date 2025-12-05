# 🌍 VOYAGO - Smart Collaborative Trip Planning Platform

**Voyago** is a modern, full-stack travel planning application that transforms how groups organize and manage trips together. Built with React, Node.js, and MySQL, Voyago combines intelligent email extraction, real-time collaboration, and comprehensive budget tracking to make travel planning effortless.

## ✨ Key Features

### 📧 **Automated Booking Management**
- **Smart Email Extraction**: AI-powered system automatically scans Gmail for flight, hotel, and rental car confirmations
- **One-Click Import**: Extract booking details from emails and add to your itinerary instantly
- **Duplicate Detection**: Intelligent filtering prevents re-importing existing bookings

### 👥 **Real-Time Collaboration**
- **Multi-User Trip Planning**: Invite friends and family to collaborate on trips
- **Role-Based Permissions**: Organizers and members with tailored access levels
- **Live Notifications**: Stay updated on trip changes, invitations, and member activity
- **Shared Itineraries**: Everyone sees the same synchronized schedule

### 💰 **Smart Budget Management**
- **Trip Budgets**: Set and track budgets for individual trips
- **Expense Splitting**: Automated calculation of who owes what
- **Category Breakdown**: Visualize spending across accommodation, food, transport, and activities
- **Member-Level Tracking**: Monitor individual spending and budget goals
- **Debt Settlement**: Built-in system to track and settle shared expenses

### 🗓️ **Interactive Calendar & Itinerary**
- **Visual Trip Planning**: Month and list views for all your events
- **Multi-Trip Organization**: Manage multiple trips with overlapping dates
- **Event Details**: Track flights, hotels, activities, and transportation
- **Timeline Management**: Automatic scheduling and conflict detection

### 🗺️ **Maps & Location Intelligence**
- **Interactive Maps**: Visualize all destinations and waypoints
- **Google Maps Export**: Generate KML files to view itineraries in Google Maps
- **Geocoding**: Automatic location detection and coordinate mapping
- **Location-Based Events**: Link events to specific places with coordinates

### 🤖 **AI-Powered Assistant**
- **Smart Recommendations**: Get AI suggestions for activities and attractions
- **Itinerary Optimization**: Intelligent scheduling assistance
- **Natural Language Queries**: Ask questions about your trip plans

## 🛠️ Tech Stack

**Frontend**
- React 19 with Hooks & Context API
- React Bootstrap for responsive UI
- Vite for lightning-fast development
- React Router for navigation
- Lucide React for modern icons

**Backend**
- Node.js & Express.js REST API
- JWT authentication with bcrypt
- MySQL database with JSON support
- Gmail OAuth integration
- Express Rate Limiting

**AI Services**
- Python FastAPI microservice
- Gmail API integration
- Booking.com email parser
- Custom extraction algorithms

## 🚀 Quick Start

### Prerequisites
- Node.js v16+
- MySQL 8.0+
- Python 3.8+
- Gmail API credentials

🔐 Security
Secure JWT-based authentication
Password hashing with bcrypt
Rate limiting on auth endpoints
OAuth 2.0 for Gmail integration
Environment variable protection
SQL injection prevention
📄 License
This project is licensed under the MIT License.

👥 Authors
Built with ❤️ by:

Kantemir Muratov
Pranav
Tate Taguchi
🤝 Contributing
Contributions, issues, and feature requests are welcome!

### Installation

```bash
# Clone the repository
git clone https://github.com/ttaguchi17/node-app-template.git
cd node-app-template

# Backend setup
cd backend
npm install
cp .env.example .env
# Configure .env with your credentials
npm run dev

# Frontend setup (new terminal)
cd frontend
npm install
npm run dev

# Email extractor service (new terminal)
cd email_extractor
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py

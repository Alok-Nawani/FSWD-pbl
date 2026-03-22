# Team Member 1 - Login Authentication & Resume Analysis

## 📋 Assigned Modules

### 1. **Login Authentication** 🔐
- Secure user authentication system
- Session management
- Password handling
- User verification
- Login page UI/UX

### 2. **Resume Analysis** 📄
- Resume upload functionality
- AI-powered resume evaluation
- Feedback generation
- Score calculation
- Improvement suggestions

### 3. **Home Page** 🏠
- Landing page showcasing your features
- Feature highlights for Auth & Resume
- Call-to-action buttons
- Navigation to app

---

## 📁 Project Structure

```
Team_Member_1/
├── index.html                 # Home/Landing page
├── login.html                 # Login page
├── app.html                   # Main application dashboard
├── css/
│   ├── style.css             # Main styling
│   ├── landing.css           # Home page styling
│   └── ai_avatar.css         # Avatar component styling
├── js/
│   ├── config.js             # Configuration & API endpoints
│   ├── main.js               # Main app logic
│   └── modules/
│       ├── auth.js           # Authentication module (YOUR FOCUS)
│       └── resume.js         # Resume analysis module (YOUR FOCUS)
└── data/                      # Data files
    └── Resume-related data
```

---

## 🔧 Key Files to Work On

### Authentication (`js/modules/auth.js`)
- Implement login form validation
- Handle user authentication logic
- Manage session tokens
- Logout functionality
- Protected route checks

### Resume Analysis (`js/modules/resume.js`)
- File upload handling
- Resume parsing and analysis
- AI integration for feedback
- Results display
- Historical tracking

### Configuration (`js/config.js`)
- API endpoints
- Authentication tokens
- Backend URL configuration

---

## 🚀 Getting Started

1. **Setup Backend**: Ensure the backend API is running on `http://localhost:5001` or update the `API_URL` in `config.js`

2. **Login Page Flow**:
   - User enters email and password
   - Credentials validated against backend
   - JWT token stored in localStorage
   - Redirect to app.html

3. **Resume Analysis Flow**:
   - User uploads resume (PDF/DOC)
   - File sent to backend for analysis
   - AI generates evaluation report
   - Score and feedback displayed

---

## ✅ Deliverables (40% of Project)

- [ ] Functional login/logout system
- [ ] Resume upload with validation
- [ ] AI-powered resume analysis display
- [ ] User session management
- [ ] Home page with feature showcase
- [ ] Error handling and validation
- [ ] Responsive design

---

## 📞 Team Coordination

- **Member 2**: Learning Hub & Quizzes
- **Member 3**: Voice-enabled Interviews
- **Shared**: Home page design should be consistent across all versions

## Project Structure
```
Team_Member_1/
├── index.html                 # Home/Landing page
├── app.html                   # Main application interface
├── login.html                 # Authentication page
├── css/
│   ├── style.css             # Main application styles
│   └── landing.css           # Home page styles
├── js/
│   ├── config.js             # Configuration & API endpoints
│   ├── utils.js              # Utility functions
│   ├── main.js               # Application bootstrap
│   └── modules/
│       ├── auth.js           # Authentication module
│       ├── interview.js       # Mock interview logic
│       ├── navigation.js      # Navigation handler
│       └── dashboard.js       # Analytics dashboard (shared)
├── data/
│   └── interviews/           # Interview questions & data
│       ├── amazon/
│       ├── google/
│       ├── infosys/
│       ├── microsoft/
│       └── tcs/
└── README.md                 # This file

## Getting Started
1. Copy this folder to your workspace
2. Open `index.html` in browser for home page
3. Open `app.html` after login for the application
4. Configure API keys in `js/config.js`

## Key Files
- **app.html** - Main app interface with sidebar navigation
- **login.html** - Simple login form
- **js/modules/interview.js** - Interview module implementation
- **data/interviews/** - Interview question bank by company

## Sharing with Backend
- Share the `backend/` folder from main project for API endpoints
- Ensure `.env` file has required API keys (GEMINI_API_KEYS, etc.)

## Next Steps
- Coordinate with Team Member 2 & 3 for shared components
- Keep module interfaces clean for future integration
- Test all auth flows before deployment

---
**Assigned to:** Team Member 1  
**Last Updated:** March 2026

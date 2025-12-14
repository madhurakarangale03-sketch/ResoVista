# 🎓 ResoVista - Remote Classroom Platform

ResoVista is a comprehensive mobile-first Remote Classroom platform designed specifically for rural colleges with limited connectivity and resources.

## 🌟 Features

### For Students
- **Live Class Streaming** with low-data optimization
- **Gamified Learning** with educational games and leaderboards
- **Offline Content Management** for poor internet areas
- **Todo List** for assignment tracking
- **Document Manager** for study materials
- **Attendance System** with QR code scanning
- **Exam/Quiz System** with webcam monitoring
- **Chat & Call** with teachers and peers
- **Lab Simulators** with certificates
- **Notification Center** for important updates
- **Feedback System** to rate teachers and admins

### For Teachers
- **Real-time Student Monitoring** during classes
- **Live Class Interface** with screen sharing
- **Whiteboard** for interactive teaching
- **AI Assistant** for lesson planning
- **Attendance Tracking** with analytics
- **Exam Creation** with automated grading
- **Marks/Results Management**
- **Class Reports** with search functionality
- **Chat/Call System** for student communication

### For Admins
- **Central Management** for users and classes
- **Accounts Management** for fees and payments
- **Notification System** to broadcast announcements
- **Analytics Dashboard** for insights
- **Feedback Review** from students
- **Resource Allocation** management

## 🎨 Design Features

- **Mobile-First Design** optimized for smartphones
- **Vibrant Pastel Colors** (orange, green, blue)
- **Accessible Interface** with clear navigation
- **Cultural Neutrality** for regional language integration
- **Low-Bandwidth Optimized** for rural connectivity

## 🚀 Quick Start

### Prerequisites
- Node.js 18 or higher
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/resovista.git
cd resovista
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Open your browser to the local development URL (usually `http://localhost:5173`)

### Build for Production

```bash
npm run build
```

Preview production build:
```bash
npm run preview
```

## 📦 Deployment

ResoVista can be deployed to various platforms. See [DEPLOYMENT_GUIDE.md](./DEPLOYMENT_GUIDE.md) for detailed instructions.

**Quick Deploy Options:**
- **Vercel** (Recommended) - One-click deployment
- **Netlify** - Easy Git integration
- **GitHub Pages** - Free static hosting
- **Render** - With backend support
- **Firebase Hosting** - Google Cloud platform

## 🛠️ Technology Stack

- **React** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Vite** - Build tool
- **Lucide React** - Icons
- **Recharts** - Data visualization
- **Motion/React** - Animations

## 📱 User Roles

### Student Login
- Username: `student`
- Password: `student123`

### Teacher Login
- Username: `teacher`
- Password: `teacher123`

### Admin Login
- Username: `admin`
- Password: `admin123`

## 🗂️ Project Structure

```
resovista/
├── components/
│   ├── ui/                      # Reusable UI components
│   ├── AdminPanel.tsx           # Admin dashboard
│   ├── StudentDashboard.tsx     # Student dashboard
│   ├── TeacherDashboard.tsx     # Teacher dashboard
│   ├── LiveClassInterface.tsx   # Live streaming
│   ├── GamificationSection.tsx  # Games & leaderboards
│   ├── ExamQuizSystem.tsx       # Testing system
│   ├── LabSimulators.tsx        # Virtual labs
│   └── ...                      # Other components
├── styles/
│   └── globals.css              # Global styles & tokens
├── App.tsx                      # Main application
└── ...

```

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📋 Features Checklist

- ✅ Three role-based dashboards (Student, Teacher, Admin)
- ✅ Live class streaming interface
- ✅ Gamification with educational games
- ✅ Real-time monitoring for teachers
- ✅ Offline content management
- ✅ Todo list system
- ✅ Document management
- ✅ Attendance tracking (QR & manual)
- ✅ Exam/quiz system with webcam
- ✅ Marks and results management
- ✅ Chat and call functionality
- ✅ Lab simulators with certificates
- ✅ AI assistant for teachers
- ✅ Interactive whiteboard
- ✅ Notification system
- ✅ Feedback system
- ✅ Search functionality
- ✅ Responsive mobile design
- ✅ Vibrant pastel color scheme

## 🎯 Target Audience

ResoVista is specifically designed for:
- **Rural Colleges** with limited internet connectivity
- **Students** in remote areas
- **Teachers** conducting remote classes
- **Administrators** managing educational institutions

## 🔒 Security Considerations

**Note:** Current version uses client-side authentication for demonstration purposes.

For production deployment with real users:
- Implement proper backend authentication
- Use secure API endpoints
- Add data encryption
- Implement role-based access control (RBAC)
- Add session management

## 🌍 Future Enhancements

- Progressive Web App (PWA) support
- Regional language translations
- Native mobile apps (Android/iOS)
- Backend API integration
- Database persistence
- Video recording and playback
- Advanced analytics
- Parent portal

## 📄 License

This project is created for educational purposes.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## 💬 Support

For questions or support, please open an issue in the repository.

## 🙏 Acknowledgments

Built with the goal of making quality education accessible to rural communities through technology.

---

**Making Remote Education Accessible** 🎓📱🌍

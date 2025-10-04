# 🚀 Mreward PRO - Premium Rewards Platform

![Mreward PRO](https://img.shields.io/badge/Mreward-PRO-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-2.0-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20PWA-orange?style=for-the-badge)

## 📱 **Native Android App Experience**

Mreward PRO is a **premium rewards platform** that delivers a **native Android app experience** through the web. Earn coins by completing tasks, refer friends, and withdraw real money through multiple payment methods.

## ✨ **Key Features**

### 🔐 **Secure Authentication**
- Full-screen login experience like native Android apps
- Firebase-powered authentication
- Real-time user data synchronization
- Material Design inspired UI

### 💰 **Multiple Earning Methods**
- **Daily Rewards**: Claim bonus coins every 24 hours
- **Task Completion**: Complete tasks to earn coins instantly
- **Referral Program**: Earn 100 coins per successful referral
- **Streak Bonuses**: Maintain daily login streaks for extra rewards

### 💸 **Flexible Withdrawals**
- **UPI**: Minimum 2000 coins (₹200)
- **Paytm**: Minimum 5000 coins (₹500)
- **Bank Transfer**: Minimum 10000 coins (₹1000)
- Real-time withdrawal history tracking

### 📱 **Native App Features**
- **Bottom Navigation**: Android-style navigation
- **Material Design**: Modern UI components
- **Smooth Animations**: Native app feel
- **PWA Ready**: Install as app on mobile devices
- **Responsive Design**: Works on all screen sizes

## 🛠 **Technology Stack**

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase (Authentication + Firestore)
- **UI Framework**: Material Design principles
- **PWA**: Service Worker ready
- **Hosting**: Firebase Hosting compatible

## 🚀 **Quick Start**

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mreward-pro.git
   cd mreward-pro
   ```

2. **Firebase Setup**
   - Create a Firebase project at https://console.firebase.google.com
   - Enable Authentication (Email/Password)
   - Create Firestore database
   - Replace Firebase config in `index.html`

3. **Deploy**
   ```bash
   # Using Firebase Hosting
   npm install -g firebase-tools
   firebase login
   firebase init hosting
   firebase deploy
   
   # Or use any static hosting service
   # Upload index.html and other files
   ```

## 📊 **Database Structure**

### Users Collection
```javascript
{
  uid: "user-id",
  email: "user@example.com",
  coins: 1500,
  totalTasks: 25,
  totalEarned: 2000,
  referralCode: "ABC123",
  lastClaim: "2024-01-15",
  createdAt: timestamp
}
```

### Tasks Collection
```javascript
{
  id: "task-id",
  title: "Complete Survey",
  desc: "Fill out a short survey",
  coins: 100,
  active: true,
  createdAt: timestamp
}
```

### Withdrawal Requests Collection
```javascript
{
  userId: "user-id",
  method: "UPI",
  destination: "user@upi",
  coins: 2000,
  status: "pending",
  createdAt: timestamp
}
```

## 🎨 **UI Components**

### 🔐 **Authentication Screen**
- Full-screen gradient background
- Animated logo with glassmorphism effect
- Material Design form inputs
- Smooth transition animations

### 🏠 **Home Dashboard**
- Stats grid with coin balance
- Daily reward claiming
- Quick stats overview
- Material Design cards

### 🎯 **Tasks Section**
- Clean task listing
- One-tap claiming system
- Real-time updates
- Progress indicators

### 🏆 **Rewards & Referrals**
- Referral code display
- Social media sharing
- Withdrawal options
- Transaction history

### 👤 **User Profile**
- Avatar with initials
- Account statistics
- Recent activity feed
- Logout functionality

## 📱 **PWA Features**

The app is **Progressive Web App (PWA) ready** with:

- **Installable**: Add to home screen
- **Offline Ready**: Service worker support
- **Native Feel**: Full-screen experience
- **Push Notifications**: Coming soon
- **App Icon**: Custom branding

## 🔧 **Configuration**

### Firebase Config
Update the Firebase configuration in `index.html`:

```javascript
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "123456789",
  appId: "your-app-id"
};
```

### Customization Options
- **App Name**: Change in HTML title and headers
- **Colors**: Modify CSS custom properties in `:root`
- **Coin Values**: Adjust reward amounts in JavaScript
- **Withdrawal Limits**: Update minimum withdrawal amounts

## 📈 **Performance**

- **Fast Loading**: Optimized assets and code
- **Smooth Animations**: 60fps transitions
- **Real-time Updates**: Firebase listeners
- **Mobile Optimized**: Touch-friendly interface
- **Responsive**: Works on all devices

## 🔒 **Security Features**

- **Firebase Security Rules**: Database protection
- **Client-side Validation**: Input sanitization
- **Transaction Safety**: Atomic operations
- **User Authentication**: Secure login system
- **Data Privacy**: Minimal data collection

## 🌟 **Advanced Features (Coming Soon)**

- **AI Task Personalization**: Machine learning recommendations
- **Geo-targeted Tasks**: Location-based offers
- **Premium Subscriptions**: Ad-free experience
- **Cryptocurrency Withdrawals**: Bitcoin, Ethereum support
- **Multi-language Support**: Hindi, English, and more

## 📱 **Mobile App Development**

This web app can be easily converted to:
- **React Native** for iOS and Android
- **Flutter** for cross-platform development
- **Capacitor/Cordova** for hybrid apps
- **Electron** for desktop applications

## 🤝 **Contributing**

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 **Support**

For support and queries:
- **Email**: support@mrewardpro.com
- **Telegram**: @MrewardPROSupport
- **WhatsApp**: +91-XXXXXXXXXX

## 🙏 **Acknowledgments**

- **Firebase** for backend services
- **Material Design** for UI inspiration
- **Progressive Web Apps** for native app experience
- **Open Source Community** for continuous support

---

**Made with ❤️ in India** 🇮🇳

**© 2024 Mreward PRO. All rights reserved.**
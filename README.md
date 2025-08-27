# Urban Drainage Management System

A comprehensive web-based monitoring and management system for urban drainage infrastructure, providing real-time data visualization, analytics, and system control capabilities.

## 🌟 Features

### Core Functionality
- **Real-time Monitoring**: Live tracking of water levels, humidity, TDS levels, and water temperature
- **Interactive Dashboard**: Comprehensive data visualization with charts and statistics
- **Predictive Analytics**: AI-powered flood prediction and system failure forecasting
- **GIS Integration**: Interactive mapping of drainage infrastructure
- **User Authentication**: Secure login/signup system with Firebase integration
- **Responsive Design**: Mobile-friendly interface across all devices

### Technical Monitoring Parameters
- **Water Level**: Real-time depth monitoring in centimeters
- **Humidity**: Ambient air moisture percentage around drainage systems
- **TDS Level**: Total Dissolved Solids measurement in ppm (water quality indicator)
- **Water Temperature**: Temperature readings in Celsius

## 🏗️ Project Structure

```
Drainage Project/
├── index.html              # Landing page with system overview
├── Pages/
│   ├── dashboard.html      # Main monitoring dashboard
│   └── login&signup.html  # Authentication portal
├── Images/
│   ├── image.png          # Background image
│   ├── login.jpg          # Login page background
│   └── logo.png           # System logo
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for Firebase services
- Local web server (optional, for development)

### Installation & Usage

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser to view the landing page
3. **Navigate to Login** by clicking the "Dashboard Login" button
4. **Create an Account** or sign in with existing credentials
5. **Access the Dashboard** to view real-time monitoring data

### Development Setup
For local development:
1. Serve the files using a local web server (e.g., Python HTTP server, Node.js serve, etc.)
2. Open the served URL in your browser

## 🔧 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Authentication**: Firebase Auth
- **Database**: Firebase Realtime Database
- **Icons**: Font Awesome
- **Styling**: Custom CSS with CSS variables

## 📊 Firebase Configuration

The system uses Firebase for:
- User authentication and management
- Real-time data storage and retrieval
- Secure database operations

**Firebase Project**: `drainage-c23d2`
**Database Region**: Asia Southeast 1

## 🎨 Design Features

- **Modern UI**: Clean, professional interface with water-themed design elements
- **Responsive Layout**: Adapts to desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations and transitions
- **Color Scheme**: Blue-themed palette reflecting water management
- **Accessibility**: WCAG compliant design considerations

## 📱 Pages Overview

### Landing Page (`index.html`)
- System introduction and overview
- Feature highlights and statistics
- Call-to-action for dashboard access
- Contact information

### Dashboard (`Pages/dashboard.html`)
- Real-time sensor data visualization
- Interactive charts with time range controls
- System status monitoring
- Export and alert functionality

### Login/Signup (`Pages/login&signup.html`)
- Modern sliding panel authentication
- Social login options
- Password recovery
- Smooth transition animations

## 🔍 Key Components

### Monitoring Parameters
1. **Water Level**: Critical for flood prediction and system capacity
2. **Humidity**: Environmental moisture affecting drainage performance
3. **TDS Level**: Water quality indicator for pollution monitoring
4. **Water Temperature**: Affects water flow and system efficiency

### Chart Features
- Real-time data updates
- Multiple time ranges (1h, 6h, 24h)
- Interactive tooltips
- Responsive design
- Export capabilities

## 🛡️ Security Features

- Firebase Authentication with email/password
- Secure database rules
- Protected user data storage
- Session management

## 🌐 Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## 📈 Performance

- Optimized asset loading
- Efficient chart rendering
- Minimal external dependencies
- Fast Firebase data retrieval

## 🤝 Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This project is proprietary software. All rights reserved.

## 🆘 Support

For technical support or questions:
- Email: info@drainagemanagement.com
- Phone: +1 (234) 567-890

## 🔄 Version History

- **v1.0** (Current): Initial release with core monitoring features
- Planned: Advanced analytics, mobile app, API integration

## 🎯 Use Cases

- Municipal water management departments
- Urban planning organizations
- Environmental monitoring agencies
- Civil engineering projects
- Disaster management teams

## 📊 Data Sources

The system currently uses simulated sensor data from Firebase Realtime Database. Integration with physical IoT sensors is supported through the existing Firebase infrastructure.

## 🚨 Alert System

The dashboard includes alert functionality for:
- Critical water level thresholds
- System malfunctions
- Maintenance requirements
- Environmental warnings

## 📋 Future Enhancements

- [ ] Mobile application
- [ ] Advanced predictive models
- [ ] Multi-language support
- [ ] API for third-party integration
- [ ] Historical data analysis
- [ ] Automated reporting
- [ ] SMS/Email alerts
- [ ] Multi-tenant support

---

**Built with ❤️ for better urban water management**

# P.T.Lee CNCET Canteen Management System

A comprehensive canteen management system with separate portals for students and administrators.

## 🚀 Features

### Login Portal (`login.html`)
- Unified entry point for both students and administrators
- User type selection (Student/Admin)
- Secure authentication
- Modern, responsive UI with animations
- Real-time validation

### Student Portal (`student.html`)
- Quick payment system
- Balance management
- Transaction history
- Live ticker for updates
- Sound notifications
- Multi-language support
- QR code scanning capability

### Admin Portal (`admin.html`)
- AI-powered liquidity terminal
- Real-time monitoring dashboard
- Student account management
- Transaction tracking
- QR code scanner for quick processing
- Excel export functionality
- Advanced analytics

## 🔐 Login Credentials

### Admin Access
- **Username:** `admin`
- **Password:** `admin123`

### Student Access
- Any valid student credentials (currently accepts any username/password for demo purposes)
- You can customize the authentication logic in `login.html`

## 📁 File Structure

```
student-and-admin/
├── login.html      # Main entry point
├── student.html    # Student portal
├── admin.html      # Admin portal
└── README.md       # Documentation
```

## 🎯 Getting Started

1. Open `login.html` in your web browser
2. Select your user type (Student or Admin)
3. Enter your credentials
4. Click "Login" to access your portal

## 🛠️ Customization

### Authentication
Edit the authentication logic in `login.html` (around line 290):

```javascript
if (selectedUserType === 'student') {
    // Add your student validation logic here
    authenticated = true;
} else if (selectedUserType === 'admin') {
    // Admin validation
    if (username === 'admin' && password === 'admin123') {
        authenticated = true;
    }
}
```

### Styling
Both portals use a dark theme with modern UI elements. You can customize colors by modifying the CSS variables at the top of each file.

## 📱 Responsive Design

All pages are fully responsive and work on:
- Desktop browsers
- Tablets
- Mobile devices

## 🔧 Technologies Used

- HTML5
- CSS3 (with animations)
- Vanilla JavaScript
- QR Code Scanner (html5-qrcode)
- Excel Export (xlsx library)

## 📄 License

© 2026 P.T.Lee CNCET. All rights reserved.

## 🤝 Support

For any issues or questions, please contact your system administrator.
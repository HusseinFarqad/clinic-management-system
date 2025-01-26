# Clinic Management System

A comprehensive web application built with Node.js and Express that helps medical clinics manage their day-to-day operations. The system provides a robust platform for managing patients, doctors, appointments, and medical records while ensuring data security and ease of use.

## 🌟 Features

- **Multi-Clinic Support**
  - Individual clinic profiles and dashboards
  - Customizable clinic information and settings
  - Location-based clinic mapping using Mapbox

- **User Management**
  - Role-based access control (Admin, Doctor)
  - Secure authentication using Passport.js
  - Profile management with image upload capability

- **Patient Management**
  - Comprehensive patient records
  - Medical history tracking
  - Visit documentation
  - Contact information management

- **Administrative Features**
  - System-wide management dashboard
  - User activity monitoring
  - Data backup and security measures

- **Additional Features**
  - Responsive design for mobile access
  - Image upload and management
  - Interactive location mapping
  - Flash notifications for user feedback

## 🚀 Tech Stack

- **Backend**
  - Node.js
  - Express.js
  - MongoDB with Mongoose
  - Passport.js for authentication

- **Frontend**
  - EJS templating
  - Bootstrap for responsive design
  - JavaScript

- **APIs & Services**
  - Mapbox for location services
  - Cloudinary for image storage
  - Express-session for session management

- **Security**
  - Helmet.js for security headers
  - Express-mongo-sanitize for injection prevention
  - Environment variables for configuration

## 📦 Installation

1. Clone the repository
```bash
git clone https://github.com/HusseinFarqad/clinic-management-system.git
cd clinic-management-system
```

2. Install dependencies
```bash
npm install
```

3. Create a .env file in the root directory and add your configuration:
```env
NODE_ENV=development
PORT=3000
MONGODB_URI=mongodb://localhost:27017/clinic-management
MAPBOX_TOKEN=your_mapbox_token
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
```

4. Start the development server
```bash
npm run dev
```

## 🔧 Configuration

The system requires several environment variables to be set:

- `NODE_ENV`: Set to 'development' or 'production'
- `PORT`: Server port number
- `MONGODB_URI`: MongoDB connection string
- `MAPBOX_TOKEN`: Mapbox API token for location services
- `CLOUDINARY_*`: Cloudinary credentials for image storage

## 🛠️ Usage

After installation, you can:

1. Create an admin account using the registration page
2. Log in to access the dashboard
3. Add doctors and manage their profiles
4. Create and manage patient records
5. Track patient visits and medical history
6. Upload and manage clinic images
7. View clinic locations on the integrated map

## 🔒 Security Features

- Session management with express-session
- Password hashing with passport-local
- XSS protection with helmet.js
- MongoDB injection prevention
- CSRF protection
- Secure cookie configuration

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📸 Screenshots

![Dashboard](./screenshots/dashboard.png)
*Admin Dashboard View*

![Patient Management](./screenshots/patient-management.png)
*Patient Management Interface*

![Clinic Mapping](./screenshots/clinic-mapping.png)
*Clinic Location Mapping*

## 🎯 Future Enhancements

- [ ] Appointment scheduling system
- [ ] Email notification system
- [ ] Medical inventory management
- [ ] Patient portal access
- [ ] Mobile application
- [ ] Automated backup system
- [ ] Advanced reporting features

## 👥 Author

**Hussein Farqad**
- GitHub: [@HusseinFarqad](https://github.com/HusseinFarqad)

## 💬 Contact

If you have any questions or suggestions, please feel free to reach out:

- Create an issue in this repository
- Contact me via [GitHub](https://github.com/HusseinFarqad)

---
⭐️ If you find this project helpful, please give it a star on GitHub!

# World on a Plate 🌍🍽️

A beautiful, fully responsive cooking recipe website featuring authentic dishes from every continent around the world. Built with HTML, CSS, JavaScript, and Firebase for secure authentication.

## ✨ Features

- **Global Recipe Collection**: Recipes from 5 continents and 15+ countries
- **Beautiful UI/UX**: Modern design with smooth animations and hover effects
- **User Authentication**: Sign up, sign in, and sign out functionality using Firebase
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Recipe Tabs**: Browse recipes by continent with smooth transitions
- **Contact Form**: Get in touch with the team
- **Professional Color Scheme**: 
  - Cream background (#F5F5DC)
  - Olive green headings (#556B2F)
  - Burnt orange CTAs (#CC5500)

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Firebase account (free tier available)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone or download the project files**
   ```bash
   git clone <repository-url>
   cd world-on-a-plate
   ```

2. **Set up Firebase**
   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project
   - Enable Authentication (Email/Password)
   - Get your Firebase configuration

3. **Configure Firebase**
   - Open `script.js`
   - Replace the `firebaseConfig` object with your own configuration:
   ```javascript
   const firebaseConfig = {
       apiKey: "your-api-key",
       authDomain: "your-project.firebaseapp.com",
       projectId: "your-project-id",
       storageBucket: "your-project.appspot.com",
       messagingSenderId: "your-sender-id",
       appId: "your-app-id"
   };
   ```

4. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience

## 🎨 Design Features

### Color Palette
- **Background**: Cream (#F5F5DC) - Warm, inviting background
- **Headings**: Olive Green (#556B2F) - Natural, earthy tones
- **Call-to-Actions**: Burnt Orange (#CC5500) - Warm, appetizing accent

### Typography
- **Headings**: Playfair Display (elegant serif font)
- **Body Text**: Open Sans (clean, readable sans-serif)

### Layout
- **Hero Section**: Eye-catching introduction with call-to-action
- **About Section**: Information about the website with statistics
- **Recipe Showcase**: Organized by continent with tabbed navigation
- **Contact Form**: Easy way to get in touch
- **Responsive Footer**: Links and social media connections

## 🔧 Technical Implementation

### Frontend Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Interactive functionality and Firebase integration

### Firebase Services
- **Authentication**: User sign up, sign in, and sign out
- **Real-time Database**: User data storage (can be extended)
- **Hosting**: Deploy your website (optional)

### Key Features
- **Modal System**: Clean sign in/sign up forms
- **Form Validation**: Client-side validation with user feedback
- **Smooth Scrolling**: Navigation between sections
- **Responsive Images**: Optimized image loading with placeholders
- **Notification System**: User feedback for actions

## 📱 Responsive Design

The website is fully responsive and works on:
- **Desktop**: Full layout with side-by-side content
- **Tablet**: Adjusted spacing and navigation
- **Mobile**: Stacked layout with mobile-optimized navigation

## 🌍 Recipe Categories

### Asia
- **Thailand**: Pad Thai
- **India**: Biryani
- **Japan**: Sushi

### Europe
- **Spain**: Paella
- **Italy**: Pasta Carbonara
- **France**: Coq au Vin

### Africa
- **Morocco**: Tagine
- **Nigeria**: Jollof Rice
- **South Africa**: Bobotie

### Americas
- **Mexico**: Tacos
- **USA**: BBQ Ribs
- **Brazil**: Feijoada

### Australia
- **Australia**: Pavlova
- **Australia**: Australian Meat Pie
- **Australia**: Lamington

## 🚀 Deployment

### Option 1: Firebase Hosting (Recommended)
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting`
4. Deploy: `firebase deploy`

### Option 2: Traditional Web Hosting
- Upload all files to your web hosting provider
- Ensure Firebase configuration is correct
- Test authentication functionality

### Option 3: GitHub Pages
- Push to GitHub repository
- Enable GitHub Pages in repository settings
- Update Firebase authentication domains

## 🔒 Security Considerations

- Firebase handles authentication security
- No sensitive data stored in client-side code
- HTTPS recommended for production
- Input validation implemented
- XSS protection through proper DOM manipulation

## 🛠️ Customization

### Adding New Recipes
1. Add recipe data to the HTML structure
2. Update CSS for new recipe cards
3. Add JavaScript functionality if needed

### Changing Colors
1. Update CSS variables in `styles.css`
2. Maintain contrast ratios for accessibility
3. Test across different devices

### Adding New Features
1. Extend JavaScript functionality
2. Add new Firebase services if needed
3. Update HTML structure accordingly

## 📞 Support

For questions or support:
- Check the code comments for implementation details
- Review Firebase documentation for authentication setup
- Test on different browsers and devices

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Unsplash**: Beautiful food photography
- **Pexels**: Recipe videos and stock media
- **Google Fonts**: Typography
- **Firebase**: Authentication and backend services
- **Modern CSS**: Grid, Flexbox, and animations

---

**Enjoy exploring the world through food! 🌍🍽️**

*Built with ❤️ for food lovers everywhere*



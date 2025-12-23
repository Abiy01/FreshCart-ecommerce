https://ecommerce-nine-ivory-88.vercel.app/login

# 🛒 E-Commerce Website

A modern, full-featured e-commerce web application built with React and Vite. This project provides a complete shopping experience with user authentication, product browsing, shopping cart, wishlist, and secure checkout functionality.

## ✨ Features

### 🔐 Authentication & Authorization
- User registration and login
- Password reset functionality with email verification
- Protected routes for authenticated users
- Session management with token-based authentication
- Demo login for quick access

### 🛍️ Shopping Features
- **Product Browsing**: Browse products with category and brand filtering
- **Product Details**: Detailed product pages with image galleries, descriptions, and ratings
- **Shopping Cart**: Add, update, and remove items from cart
- **Wishlist**: Save favorite products for later
- **Search**: Real-time product search functionality
- **Checkout**: Secure checkout process with Stripe integration

### 🎨 User Experience
- Responsive design optimized for mobile, tablet, and desktop
- Dark mode support
- Offline detection with user notifications
- Loading states and error handling
- Toast notifications for user feedback
- Smooth animations and transitions

## 🚀 Tech Stack

### Frontend Framework
- **React 18.3** - UI library
- **Vite 7.3** - Build tool and development server
- **React Router DOM 6.26** - Client-side routing

### Styling
- **Tailwind CSS 3.4** - Utility-first CSS framework
- **Flowbite 2.5** - UI component library
- **Font Awesome 6.6** - Icon library

### State Management
- **React Context API** - Global state management
- **React Query (TanStack Query) 5.52** - Server state management and caching

### Forms & Validation
- **Formik 2.4** - Form handling
- **Yup 1.4** - Schema validation

### Additional Libraries
- **Axios 1.7** - HTTP client
- **React Slick** - Image carousel/slider
- **React Helmet 6.1** - Document head management
- **React Hot Toast 2.4** - Toast notifications
- **React Detect Offline 2.4** - Offline detection

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ecommerce
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   - Navigate to `http://localhost:5173/`

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
ecommerce/
├── src/
│   ├── assets/              # Static assets (images, logos)
│   ├── components/         # Reusable UI components
│   │   ├── CategorySlider/
│   │   ├── Footer/
│   │   ├── MainSlider/
│   │   ├── Navbar/
│   │   ├── ProductItem/
│   │   ├── Products/
│   │   ├── RedirectIfAuthenticated/
│   │   └── Spinner/
│   ├── context/            # React Context providers
│   │   ├── Auth/
│   │   ├── Cart/
│   │   ├── Products/
│   │   └── Wishlist/
│   ├── pages/              # Page components
│   │   ├── Brands/
│   │   ├── Cart/
│   │   ├── Categories/
│   │   ├── Checkout/
│   │   ├── ForgotPassword/
│   │   ├── Home/
│   │   ├── Login/
│   │   ├── MainLayout/
│   │   ├── NotFound/
│   │   ├── ProductDetails/
│   │   ├── ProtectedRoute/
│   │   ├── Register/
│   │   ├── ResetPassword/
│   │   ├── Search/
│   │   ├── VerifyCode/
│   │   └── Wishlist/
│   ├── App.jsx             # Main application component
│   ├── main.jsx            # Application entry point
│   └── index.css           # Global styles
├── public/                  # Public assets
├── index.html              # HTML template
├── package.json            # Dependencies and scripts
├── tailwind.config.js      # Tailwind configuration
├── vite.config.js          # Vite configuration
└── README.md              # Project documentation
```

## 🔑 Demo Credentials

For quick testing, you can use the demo login feature:
- **Email**: `demo1@demo.com`
- **Password**: `123456@demo`

Or click the "Demo Login" button on the login page.

## 🌐 API Integration

This application uses the [Route E-Commerce API](https://ecommerce.routemisr.com/):
- Base URL: `https://ecommerce.routemisr.com/api/v1`
- Endpoints include:
  - Authentication (signup, signin, forgot password)
  - Products (list, details, search)
  - Cart operations
  - Wishlist operations
  - Orders and checkout

## 🎨 Key Features Implementation

### Authentication Flow
1. User registration with email validation
2. Email verification for password reset
3. Secure token-based session management
4. Automatic redirect for authenticated/unauthenticated users

### Shopping Cart
- Add/remove products
- Update quantities
- Real-time price calculation
- Persistent cart data

### Product Management
- Category-based filtering
- Brand filtering
- Search functionality
- Product ratings and reviews display

## 🛠️ Development

### Code Style
- ESLint configured for code quality
- React best practices
- Component-based architecture

### State Management
- Context API for global state (Auth, Cart, Wishlist)
- React Query for server state and caching
- Local storage for persistence

## 📱 Responsive Design

The application is fully responsive and optimized for:
- 📱 Mobile devices (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Large screens (1280px+)

## 🔒 Security Features

- Protected routes for authenticated users
- Token-based authentication
- Secure password reset flow
- Input validation and sanitization

## 🚀 Deployment

The project is configured for deployment on Vercel. Build the project:

```bash
npm run build
```

The production build will be in the `dist/` directory.

## 📝 License

This project is private and proprietary.

## 👨‍💻 Author

**Abiy Aragie**

- Email: aragieabiy@gmail.com
- LinkedIn: [Abiy Aragie](https://www.linkedin.com/in/abiy-aragie-963b45388/)
- GitHub: [Abiy01](https://github.com/Abiy01)

---

Made with ❤️ and passion by Abiy Aragie

# Auction Site

## 📋 Project Overview
A fully functional eBay-style auction website built with Django that allows users to create listings, place bids, manage watchlists, and interact through comments. This project demonstrates comprehensive web development skills including database modeling, user authentication, and dynamic web interfaces.

## ✨ Key Features

### 🏠 **Active Listings Homepage**
- Displays all currently active auction listings
- Shows title, description, current price, and photos
- Clean, intuitive interface for browsing available auctions

### 📝 **Create & Manage Listings**
- User-friendly form to create new auction listings
- Required fields: title, description, starting bid
- Optional fields: image URL and category selection
- Listing creators can close auctions and declare winners

### 💰 **Bidding System**
- Secure bidding with validation rules
- Bids must meet minimum requirements (≥ starting bid and > current highest bid)
- Real-time bid tracking and winner determination
- Error handling for invalid bids

### ⭐ **Watchlist Functionality**
- Personal watchlist for tracking interesting items
- Easy add/remove toggle functionality
- Dedicated watchlist page for quick access to saved items

### 💬 **Interactive Comments**
- Comment system for each listing
- Real-time discussion between users
- Complete comment history display

### 🏷️ **Category Organization**
- Organized browsing by categories (Fashion, Electronics, Home, etc.)
- Category-specific listing pages
- Enhanced user experience through logical grouping

### 🔐 **User Authentication**
- Secure user registration and login system
- Personalized features based on user status
- Protected routes for authenticated users only

### ⚙️ **Admin Interface**
- Full Django admin integration
- Complete CRUD operations for all models
- Administrative oversight of listings, bids, and comments

## 🛠️ Technical Implementation

### **Database Models**
- **User Model**: Extended Django authentication
- **Listing Model**: Auction items with all necessary fields
- **Bid Model**: Tracking all bids with relationships
- **Comment Model**: User interactions and discussions
- **Category Model**: Organized classification system

### **Core Technologies**
- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3, Bootstrap
- **Database**: SQLite
- **Authentication**: Django's built-in system

### **Key Features Implemented**
- Model relationships and foreign keys
- Form validation and error handling
- Dynamic content rendering
- User session management
- Responsive web design

## 🎯 Learning Outcomes

This project demonstrates proficiency in:
- Django framework and MTV architecture
- Database design and ORM operations
- User authentication and authorization
- Form handling and validation
- Template rendering and inheritance
- Static file management
- Admin interface customization

# EstateConnect – Real Estate Marketplace

![EstateConnect Banner](https://via.placeholder.com/1200x400?text=EstateConnect+Real+Estate+App)  
*(Modern real estate platform connecting buyers, renters, and property owners)*

EstateConnect is a full-stack real estate web application built with **React.js**, **Node.js**, **Express**, and **MongoDB**. Users can browse properties without signing in, list their own properties with Google Maps integration, filter listings, express interest, and communicate directly via private messages.

## Features

- **Public property browsing** with advanced filters (city, type, price range)
- **Google Maps integration** — view property locations on interactive/static maps
- **Secure authentication** — Email + OTP verification + password setup
- **Dark / Light mode** support
- **Property listing** — owners add name, city, type (rent/sale), price, lat/long
- **Express Interest** — logged-in users can contact owners directly
- **Private messaging** system for deal discussions
- Responsive design & clean UI

## Tech Stack

- **Frontend**: React.js, React Router, Context API / Redux, Tailwind CSS
- **Backend**: Node.js, Express.js, JWT Authentication
- **Database**: MongoDB + Mongoose
- **Maps**: Google Maps JavaScript API
- **Other**: Axios, React Hot Toast, React Icons

## Installation & Setup

### Prerequisites
- Node.js ≥ 18
- MongoDB (local or Atlas)
- Google Maps API Key (for maps)

### Backend Setup
```bash
cd backend
npm install

# PriceWise

## Overview

PriceWise is an application designed to help users determine smart pricing and generate appealing descriptions for clothing items listed on platforms like Depop. By utilizing data from various sources, PriceWise simplifies the selling process for users.

## Features

<details>
<summary>Click to expand features</summary>

- **Smart Pricing**: Automatically suggests competitive prices based on similar items sold online.
- **Description Generation**: Provides engaging product descriptions based on user inputs and item characteristics.
- **User-Friendly Interface**: Designed with simplicity in mind, making it easy for users to navigate and utilize the app effectively.
- **Image Recognition**: Allows users to upload images and analyze them for features that influence pricing and description.

</details>

## Stretch Features

<details>
<summary>Click to expand stretch features</summary>

- **Category Filtering**: Users can filter pricing suggestions by clothing categories (e.g., dresses, shoes).
- **Saved Listings**: Users can save suggested prices and descriptions for later use.
- **Price History Tracking**: Users can view the pricing history of similar items to make informed decisions.
- **User Ratings**: Users can leave ratings and feedback on pricing suggestions to improve the system's accuracy.

</details>

## Tech Stack

- **Frontend**: React for a dynamic user interface.
- **Backend**: Node.js with Express for managing API requests and user data.
- **Database**: MongoDB for storing user profiles, pricing data, and saved listings.
- **APIs**: Integrate with eBay and Mercari APIs for market data and similar item comparisons.
- **Image Recognition**: Utilize Google Vision API for analyzing uploaded images.
- **Authentication**: JWT for secure user login and data protection.
- **Deployment**: Docker for consistent development and production environments.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/PriceWise.git
   cd PriceWise

2. **Install dependencies:**
   npm install
   cd backend
   npm install

2. **Set up environment variables:**
   MONGO_URI=your_mongo_db_uri
   JWT_SECRET=your_jwt_secret
   GOOGLE_VISION_API_KEY=your_google_vision_api_key

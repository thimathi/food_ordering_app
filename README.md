# Food Ordering App

## Project Overview
The **Food Ordering App** is a mobile application developed in Kotlin for Android devices. This app provides a seamless platform for users to browse, order, and track their favorite meals from local restaurants. The project is designed to showcase the implementation of modern Android development techniques, intuitive user experience, and integration with essential APIs for a real-world application.

## Features
- **User Authentication**: Sign up, log in, and log out securely using Firebase Authentication.
- **Restaurant Listings**: Browse a variety of restaurants with their menus.
- **Menu Management**: View detailed menus with images, descriptions, and prices.
- **Order Placement**: Add items to a cart and place orders.
- **Real-Time Order Tracking**: Track order status in real time.
- **Search & Filter**: Search restaurants by name or filter them by cuisine, ratings, or location.
- **Favorites**: Save favorite dishes or restaurants for quick access.
- **Push Notifications**: Get notifications for order status updates and special deals.

## Technologies Used
- **Programming Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **Database**: Firebase Realtime Database
- **Authentication**: Firebase Authentication
- **Cloud Storage**: Firebase Cloud Storage for storing menu images
- **APIs**: Google Maps API for restaurant locations
- **UI Design**: XML layouts with Material Design components

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/thimathi/FoodOrderingApp.git
   ```
2. Open the project in Android Studio.
3. Sync the Gradle files to download dependencies.
4. Set up Firebase for the project:
   - Go to [Firebase Console](https://console.firebase.google.com/).
   - Create a new project and connect your app to Firebase.
   - Add the `google-services.json` file to the `app/` directory.
5. Build and run the app on an emulator or a physical device.

## Usage
1. Launch the app and create an account or log in.
2. Browse through the restaurant listings.
3. Select a restaurant and view its menu.
4. Add items to the cart and place an order.
5. Track the order in real time and enjoy your meal!

## Screenshots
- **Login Screen**: User authentication interface.
- **Restaurant List**: Display of all available restaurants.
- **Menu Page**: Details of food items available.
- **Cart and Checkout**: Summary of selected items and order placement.
- **Order Tracking**: Real-time updates on order status.

## Project Structure
```
FoodOrderingApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/thimathi/foodorderingapp/
│   │   │   ├── res/
│   │   │   ├── AndroidManifest.xml
│   ├── build.gradle
├── google-services.json
└── README.md
```

## Roadmap
- Add a reward points system for frequent users.
- Include multi-language support.
- Enable integration with third-party payment gateways like Stripe or PayPal.
- Expand the admin interface for restaurant owners to manage their listings.

## Contribution
This is a solo project, but contributions and suggestions are welcome. Please open an issue or submit a pull request for any improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or feedback, feel free to contact me:
- **GitHub**: [Thimathi](https://github.com/thimathi)
- **Email**: [Thimathi](mailto:cmtd.2001@gmail.com)


---
Thank you for checking out my Food Ordering App project! Your feedback and suggestions are always appreciated.


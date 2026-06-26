# Grad Store App 🛒

A comprehensive e-commerce app for providing graduation project supplies in Yemen, with support for suppliers and points of sale, built using Flutter and Clean Architecture.

![Flutter](https://img.shields.io/badge/Flutter-3.19.0-blue?style=flat-square&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.3.0-blue?style=flat-square&logo=dart)
![BLoC](https://img.shields.io/badge/BLoC-8.0.0-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)


## 🚀 Key Features

- Integrated User System: User login (students/graduates), suppliers, and point of sale.
- Smart Browsing and Categorization: Categorize products by academic discipline (Engineering, Medicine, Graphics, AI).
- Flexible Shopping Cart: Add/delete products, update quantities, calculate totals.
- Payment: Multiple payment methods (Wallet, Card, PayPal, Google Pay).
- My Orders: Track orders, reorder, filter (Active, Completed, Cancelled).
- Suppliers: A dashboard for managing products and sales.
- Point of Sale: A dedicated interface for direct sales.
- Advanced Search: Filter by category, price, and rating.
- Ratings and Reviews: Rate products and write comments.
- Favorites and Wishlist: Save favorite products.
- Maps: Locate delivery locations.


## 🛠 Technologies Used

| Domain | Technologies |
|--------|----------|
| Interface: Flutter, Dart |  | State Management | BLoC (Cubit) |
| Network | Dio, Retrofit |
| Local Storage | SharedPreferences, Hive |
| Dependency Injection | GetIt |
| Image Handling | CachedNetworkImage |
| Functional Programming | Dartz (Either) |
| APIs | External REST API (JWT) |


## 📁 Project Structure
```
lib/
├── core/
│   ├── constants/
│   ├── errors/
│   ├── network/
│   ├── theme/
│   ├── utils/
│   └── widgets/
├── features/
│   ├── auth/
│   ├── cart/                
│   ├── categories/
│   ├── favorites/            
│   ├── home/
│   ├── map/
│   ├── offers/
│   ├── orders/
│   ├── products/             
│   ├── profile/
│   ├── sellershop/
│   └── studentprofile/
└── main.dart
```

## 📱 Screenshots

<div align="center">
  <img src="https://i.imgpeek.com/V2FvUfn1W0x1" alt="1" width="1000"/>
  <img src="https://i.imgpeek.com/xgAWC4yAloL9" alt="2" width="1000"/>
  <img src="https://i.imgpeek.com/pqqNhr5qqyi2" alt="3" width="1000"/>
  <img src="https://i.imgpeek.com/8cycV93Eo6Qm" alt="4" width="1000"/>
  <img src="https://i.imgpeek.com/1sGo9Slwu6z-" alt="5" width="1000"/>
  <br/><br/>
  <em>Grad Store</em>
</div>

## 📦 Installation

``` bash
git clone https://github.com/mm778877331-stack/grad-store-app.git
cd grad-store-app
flutter pub get
flutter run
```

## 🤝 Contributing  
Pull requests are welcome!

## 📬 Contact

- Email: qwererrff@gmail.com
- GitHub: [mm778877331-stack](https://github.com/mm778877331-stack)
- LinkedIn: [Mohammad Al-Baou](https://www.linkedin.com/in/mohammed-tawfiq-9798903b3?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) (Optional)

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

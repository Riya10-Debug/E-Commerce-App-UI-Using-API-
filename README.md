#  Flutter E-Commerce App UI (API Integration)

A Flutter application that displays products in a grid layout by fetching data from a free online API. This project demonstrates API integration, JSON parsing, and UI design using `GridView`.

---

##  API Used

* https://fakestoreapi.com/products

---

##  Features

*  Fetch product data from API
*  Display product images
*  Show product name and price
*  Grid layout using `GridView`
*  Dynamic data rendering
*  Clean and responsive UI

---

##  Technologies Used

* Flutter
* Dart
* HTTP package (for API calls)

---

##  Project Structure

```id="api9d2"
lib/
 └── main.dart
models/
 └── product_model.dart   (optional)
services/
 └── api_service.dart    (optional)
```

---

##  Getting Started

Follow these steps to run the project locally:

### Prerequisites

* Install Flutter SDK
* Install Android Studio / VS Code
* Set up an emulator or connect a physical device

---

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-ecommerce-ui.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flutter-ecommerce-ui
   ```

3. Get dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

---

##  Dependency Setup

Add this to your `pubspec.yaml`:

```yaml id="http1x"
dependencies:
  http: ^0.13.6
```

---

##  How It Works

* Uses `http` package to fetch data from the API
* API returns product data in JSON format
* JSON is parsed into Dart objects (model class optional)
* `FutureBuilder` is used to handle async data
* `GridView.builder` displays products in a grid
* Each product card includes:

  * Image (`Image.network`)
  * Product name (`Text`)
  * Price (`Text`)

---

##  Future Improvements

* Add product detail screen
* Implement cart functionality
* Add search and filter options
* Improve UI with animations
* Add error handling and loading indicators

---

##  Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---


##  Author

Riya Patani

---

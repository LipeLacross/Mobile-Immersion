## 🌐 [English Version of README](README_EN.md)

# Mobile-Immersion

Food ordering app developed during Alura’s Mobile Immersion using Flutter. The project features category-based navigation, custom assets, ratings, and a modern UI to simulate a real food delivery experience.

- [Figma Design Prototype](https://www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imers%C3%A3o?node-id=7-47&p=f)
- [Project IDX (Google Cloud IDE)](https://idx.google.com/)
- [Alura Mobile Immersion Guide](https://grupoalura.notion.site/Imers-o-Mobile-Guia-de-Mergulho-1ba379bdd09b80e3ac18c8512f31530d?pvs=4)

# TechTaste

Food delivery app developed during Alura’s Mobile Immersion, using Flutter to create a modern, responsive, and cross-platform experience. The project simulates a restaurant marketplace, allowing users to navigate by categories, view establishments, add dishes to the cart, and checkout, with custom assets and an interface inspired by leading apps in the market.

## 🔨 Project Features

- Custom splash screen
- Restaurant listing with ratings, distance, and categories
- Filtering and navigation by dish categories (starters, mains, pasta, desserts, drinks)
- Detailed restaurant and dish views
- Add dishes to the cart with quantity control
- Simple checkout and modern UI
- Responsive interface based on Material Design
- Custom assets for banners, icons, and dish images

### Project Visual Example

<div align="center"> <table> <tr> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/e77be6d2-c164-4782-a0a1-dc08ac5d946e" width="200" alt="Tela 1"/> </td> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/3e42d48c-ccef-42fa-aa0d-af71907e0842" width="200" alt="Tela 2"/> </td> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/73aa3266-af74-4427-888e-742164ecd892" width="200" alt="Tela 3"/> </td> </tr> <tr> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/7ee71d28-97eb-4c08-90f9-85688afe6c63" width="200" alt="Tela 4"/> </td> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/48971992-0be3-4b7a-a957-bb7dc1bed4e8" width="200" alt="Tela 5"/> </td> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/29e44c64-7b7e-4c35-893d-3ac5cd3577c0" width="200" alt="Tela 6"/> </td> </tr> <tr> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/83bf845a-af88-410b-856d-cda6c215fe8c" width="200" alt="Tela 7"/> </td> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/b15e5386-8c09-431d-afbb-4150b46694c1" width="200" alt="Tela 8"/> </td> <td align="center" width="220"> <img src="https://github.com/user-attachments/assets/af369f8a-f964-4fe3-8f44-8a5ed1f79046" width="200" alt="Tela 9"/> </td> </tr> </table> </div> <div align="left">

</div>

## ✔️ Techniques and Technologies Used

- **Flutter** (cross-platform framework)
- **Dart** (main language)
- **Provider** (state management)
- **Material Design**
- **Local assets** (images, icons, JSON data)
- **Modular structure** (models, data, UI)
- **Basic unit tests**
- **Project IDX** for cloud development (optional, [learn more](https://idx.google.com/))

## 📁 Project Structure

- **lib/**
    - **data/**: Data sources and loading (`categories_data.dart`, `restaurant_data.dart`)
    - **model/**: Domain models (`dish.dart`, `restaurant.dart`)
    - **ui/**: User interface, separated by screens and components
        - **_core/**: Themes, colors, cart provider, common widgets
        - **home/**: Home screen and widgets
        - **restaurant/**: Restaurant detail screen
        - **splash/**: Splash screen
    - **main.dart**: Application entry point

- **assets/**
    - **banners/**: Promotional and splash images
    - **categories/**: Dish category icons
    - **dishes/**: Dish images
    - **restaurants/**: Restaurant images
    - **others/**: Auxiliary icons (star, card flag)
    - **data.json**: Restaurant data

- **android/**, **ios/**, **web/**, **linux/**, **macos/**, **windows/**: Platform-specific folders for build and native configuration

- **test/**: Unit and widget tests

- **pubspec.yaml**: Project configuration and dependencies

## 🛠️ How to Open and Run the Project

To start the project locally, follow these steps:

1. **Make sure Node.js is installed** (for auxiliary tools):
   ```bash
   node -v
   ```
   If not installed, download it from [nodejs.org](https://nodejs.org/).

2. **Clone the repository**:
   ```bash
   git clone 
   ```

3. **Install Flutter dependencies**:
   ```bash
   flutter pub get
   ```

4. **Run the project**:
    - To run in debug mode:
      ```bash
      flutter run
      ```
    - To run in the browser:
      ```bash
      flutter run -d chrome
      ```
    - To run on desktop:
      ```bash
      flutter run -d 
      ```

## 🌐 Deploy

- **Web**: To build for the web, use:
  ```bash
  flutter build web
  ```
  The final files will be in `build/web/`, ready for deployment to any static hosting service.

- **Android/iOS**: Use Flutter's standard commands:
  ```bash
  flutter build apk   # Android
  flutter build ios   # iOS
  ```

- **Desktop**:
  ```bash
  flutter build windows
  flutter build macos
  flutter build linux
  ```

- **Project IDX**: You can use [Project IDX](https://idx.google.com/) for cloud development, with Flutter support, web and Android preview, real-time collaboration, Google Cloud integration, and Gemini AI support.

---

> **References and Guides**
>
> - [Official Alura Mobile Immersion Guide](https://grupoalura.notion.site/Imers-o-Mobile-Guia-de-Mergulho-1ba379bdd09b80e3ac18c8512f31530d?pvs=4)
> - [Figma Project](https://www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imers%C3%A3o?node-id=7-47&p=f)
> - [Project IDX (Google Cloud IDE)](https://idx.google.com/)

---

This project was created for educational purposes during Alura’s Mobile Immersion, demonstrating scalable architecture, custom assets, and Flutter best practices[1].

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/55317053/5929c60f-b9be-42a6-81c0-22e12261296a/directory_listing.txt

---
Resposta do Perplexity: pplx.ai/share
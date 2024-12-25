# Ai-Image-Generator-in-Flutter

An AI-powered Flutter application built with **Clean Architecture** principles to generate images using the Imagine API. The project leverages state management using **flutter_bloc**, networking with **Dio**, and structured code organization.

## Features

- Generate images using the [Imagine API](https://api.vyro.ai/v1/imagine/api/generations).
- Simple and intuitive interface: Enter a prompt, and the app generates an AI-powered image based on the input.
- Organized project structure following Clean Architecture.
- State management with `flutter_bloc`.
- Optimized API integration with `dio`.

## How It Works

1. Enter a descriptive prompt in the app's input field.
2. The app sends the prompt to the Imagine API.
3. The API generates an image based on the prompt and returns it to the app.
4. The generated image is displayed on the screen.

## Getting Started

### Prerequisites

1. Install Flutter: [Flutter Installation Guide](https://flutter.dev/docs/get-started/install).
2. Add the following dependencies to your `pubspec.yaml` file:
   ```yaml
   dependencies:
     flutter_bloc: ^8.1.6
     bloc: ^8.1.4
     dio: ^latest
   ```

### API Setup

1. Obtain your API key for the Imagine API from [Imagine](https://www.imagine.art).
2. Update the `api_key` in the `api_constants.dart` file:
   ```dart
   const String baseUrl = 'https://api.vyro.ai/v1/imagine/api/generations';
   const String apiKey = 'YOUR_API_KEY';
   ```

### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-image-generation.git
   cd ai-image-generation
   ```

2. Get dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to contribute or raise issues to improve the project!


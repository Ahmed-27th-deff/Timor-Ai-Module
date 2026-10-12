# Timor AI

Timor AI is a smart Flutter-based personal assistant application designed to help users interact with an AI chatbot, upload images for AI-powered analysis, and use voice-driven conversations. The app combines modern UI design with Gemini AI, speech recognition, and text-to-speech features to create an intuitive and engaging assistant experience.

## Demo Video

[Watch the Timor AI demo](https://drive.google.com/file/d/1uFCRUJrR8IR65oLvSYvwq7sIkuob081V/view?usp=sharing)

## Project Summary

Timor AI is built to offer a simple and friendly AI assistant for everyday use. Users can:

- Chat with an AI assistant
- Send text prompts to Gemini
- Upload images for visual AI queries
- Speak naturally using voice input
- Receive spoken responses through text-to-speech
- Experience smooth animations and a polished dark UI

This project is a modern AI app prototype focused on accessibility, interactivity, and user experience.

## App Description

Timor AI acts like a digital companion that understands text and voice commands. It allows the user to:

1. Open the home screen and access the main chat flow
2. Send a message to the AI assistant
3. Attach an image for enhanced multimodal interaction
4. Use the virtual assistant screen for voice interaction
5. Listen to AI responses spoken aloud

The app is designed for mobile devices and built with Flutter, making it easy to run on multiple platforms including Android, iOS, Linux, Windows, macOS, and web.

## Main Pages and Screens

1. Home Screen
   - Displays the Timor app branding
   - Redirects users to the AI chat experience

2. Chat Screen
   - Enables text-based conversation with Gemini
   - Allows users to send image attachments
   - Shows message bubbles for user and AI responses

3. Virtual Assistant Screen
   - Uses microphone input for voice commands
   - Converts speech to text
   - Sends the recognized text to Gemini
   - Reads the AI output using Flutter TTS
   - Provides animated assistant feedback

## Features

1. Gemini-powered AI chat
2. Image upload support for multimodal prompts
3. Speech-to-text input
4. Text-to-speech AI responses
5. Dark modern user interface
6. Animated assistant feedback using Lottie
7. Custom branding and splash screen
8. Cross-platform Flutter support
9. Friendly, responsive app layout
10. Easy-to-use assistant interactions

## Technologies Used

- Flutter
- Dart
- Gemini AI (`flutter_gemini`)
- Speech recognition (`speech_to_text`)
- Text-to-speech (`flutter_tts`)
- Image picker (`image_picker`)
- Lottie animations
- Material Design UI
- Custom app icons and splash assets

## Project Structure

```text
lib/
├── main.dart
├── constants.dart
├── views/
│   ├── home_view.dart
│   ├── chat_bot_view.dart
│   └── virtual_assistant.dart
├── widgets/
│   ├── animated_speech_container.dart
│   ├── custom_circle_button.dart
│   ├── custom_text_field.dart
│   └── message.dart
assets/
├── fonts/
├── icons/
├── images/
```

## How to Run

1. Install Flutter SDK
2. Clone the project
3. Open the project directory
4. Run:

```bash
flutter pub get
flutter run
```

## Notes

This app is a useful AI assistant prototype demonstrating chat, voice, and image-based interaction with modern Flutter UI. It is suitable for mobile app demos, student projects, and AI assistant showcases.

## Author / Role

This project was developed as a Flutter app project focused on AI assistant interfaces, voice communication, and multimodal interaction.

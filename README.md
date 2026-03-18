
## Linked twitter account --> https://x.com/MAHI83926

# Bluebot

An AI-powered bot for managing Twitter pages with advanced analytics and automation features.

## Overview

Bluebot is a Flutter-based application that provides intelligent tools for managing and monitoring Twitter accounts. The application includes data visualization, Twitter account authentication, and local data storage for efficient performance across multiple platforms.

## Description

An AI powered bot for managing twitter pages. This application helps users automate and optimize their Twitter presence with real-time analytics and management tools.

## Key Features

- Twitter Account Integration: Seamless OAuth 2.0 authentication with Twitter
- Real-Time Analytics: Charts and graphs for tracking account performance
- Local Data Storage: Persistent data management with Hive database
- Cross-Platform Support: Available on iOS, Android, Web, Windows, macOS, and Linux
- Modern UI: Beautiful and responsive user interface with multiple icon libraries
- Icon Support: Font Awesome, Feather, and Lucide icon sets

## Technical Stack

Framework:
- Flutter 3.8.1+
- Dart

Core Dependencies:
- http ^1.4.0 - HTTP client for API calls
- flutter_web_auth_2 ^4.0.0-alpha.0 - OAuth authentication
- hive ^2.2.3 - Local database
- hive_flutter ^1.1.0 - Flutter Hive integration
- provider ^6.1.0 - State management
- fl_chart ^1.0.0 - Data visualization

UI Components:
- cupertino_icons ^1.0.8 - iOS-style icons
- font_awesome_flutter ^10.7.0 - Font Awesome icons
- flutter_feather_icons ^2.0.0 - Feather icons
- lucide_icons ^0.257.0 - Lucide icons

Build Tools:
- flutter_launcher_icons ^0.13.1 - App icon generator
- flutter_native_splash ^2.4.6 - Native splash screens


## Installation

Prerequisites:
- Flutter SDK 3.8.1 or higher
- Dart SDK (included with Flutter)
- Git

Steps:

1. Clone the repository:
   git clone https://github.com/OmAnand857/bluebot-app.git
   cd bluebot-app

2. Install dependencies:
   flutter pub get

3. Build app icons and splash screens:
   flutter pub run flutter_launcher_icons
   flutter pub run flutter_native_splash:create

## Getting Started

Development:

Run the app on your default device:
   flutter run

Run on a specific platform:
   flutter run -d [device-id]

Build:

Build for Android:
   flutter build apk
   flutter build appbundle

Build for iOS:
   flutter build ios

Build for Web:
   flutter build web

Build for Windows:
   flutter build windows

Build for macOS:
   flutter build macos

Build for Linux:
   flutter build linux

## Configuration

Twitter OAuth Setup:

1. Register your application at Twitter Developer Portal
2. Obtain your Client ID and Client Secret
3. Configure redirect URIs in your app configuration
4. Update the authentication endpoints in the app

Database Configuration:

The app uses Hive for local data persistence. Database is automatically initialized on app startup.

## Current Features

- Twitter Account Authentication
- User Profile Management
- Analytics Dashboard with Charts
- Data Persistence with Hive
- Cross-Platform Support
- Icon Sets Integration

## Planned Features

- Advanced AI-powered tweet scheduling
- Sentiment analysis for tweets
- Engagement analytics
- Automated tweet suggestions
- Competitor analysis
- Campaign management tools

## Building and Deployment

Android:
The app includes launcher icons and native splash screens configured for Android devices including Android 12+.

iOS:
The app is configured for iOS with custom launch screens and icons.

Web, Windows, macOS, Linux:
The app can be built for desktop and web platforms using Flutter's cross-platform capabilities.

## Dependencies

For a complete list of dependencies and their versions, see pubspec.yaml

Key Dependencies:
- flutter: Flutter SDK
- http: REST API communication
- hive: Local database
- provider: State management
- fl_chart: Charts and graphs
- flutter_web_auth_2: OAuth authentication

## Development

Code Quality:
- Uses Flutter Lints for code analysis
- Follows Dart style guidelines
- Analysis options configured in analysis_options.yaml

Testing:
- Flutter testing framework included
- Test files located in test/ directory

## Linked Resources

Twitter Account: https://x.com/MAHI83926

## Platform Support

The application supports the following platforms:

- Android (API 21+)
- iOS (11.0+)
- Web
- Windows
- macOS
- Linux

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## Support

For issues, questions, or suggestions, please open an issue on the GitHub repository or contact through the linked Twitter account.

## Getting Help

For detailed Flutter documentation:
- Lab: Write your first Flutter app
- Cookbook: Useful Flutter samples
- Online Documentation: https://docs.flutter.dev/

For more information about Flutter development, visit the official Flutter documentation with tutorials, samples, guidance on mobile development, and complete API reference.

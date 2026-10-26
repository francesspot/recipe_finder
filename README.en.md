[Polski](README.md) | **English**

# Recipe Finder

A Flutter app for finding recipes — **at an early stage**.

## Status

So far the repository contains the project setup:

- a Flutter project (`recipes_finder/`) generated for Android, iOS, web, Windows, macOS and Linux,
- the planned dependencies: `http` and `dio` (fetching recipes from an API), `cached_network_image` (dish photos) and `shared_preferences` (saving local data),
- a starter screen in `lib/main2.dart` (the default Flutter counter app).

The recipe search itself has not been implemented yet.

## Running

```bash
cd recipes_finder
flutter pub get
flutter run -t lib/main2.dart
```

Requires Flutter with Dart SDK 3.9 or newer.

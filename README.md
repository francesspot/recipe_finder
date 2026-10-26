**Polski** | [English](README.en.md)

# Recipe Finder

Aplikacja we Flutterze do wyszukiwania przepisów — **na wczesnym etapie**.

## Stan projektu

Na razie repozytorium zawiera przygotowanie projektu:

- projekt Fluttera (`recipes_finder/`) wygenerowany dla Androida, iOS, web, Windowsa, macOS i Linuxa,
- zaplanowane zależności: `http` i `dio` (pobieranie przepisów z API), `cached_network_image` (zdjęcia potraw) i `shared_preferences` (zapis danych lokalnie),
- ekran startowy w `lib/main2.dart` (domyślna aplikacja-licznik Fluttera).

Samo wyszukiwanie przepisów nie zostało jeszcze zaimplementowane.

## Uruchomienie

```bash
cd recipes_finder
flutter pub get
flutter run -t lib/main2.dart
```

Wymagany Flutter z Dart SDK 3.9 lub nowszym.

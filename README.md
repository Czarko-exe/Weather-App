# 🌦️ Weather App (Work In Progress)

Desktopowa aplikacja pogodowa zbudowana w języku **Python** przy użyciu biblioteki **PyQt5**. 
Aplikacja pobiera i wyświetla aktualne dane meteorologiczne w czasie rzeczywistym, wykorzystując integrację z zewnętrznym API.

🚧 **Status projektu:** Wersja w pełni funkcjonalna. Trwają prace z nowymi funkcjami użytkowymi.

## ✨ Główne funkcje (Features)
* **Real-time API Integration:** Pobieranie danych na żywo z OpenWeatherMap API.
* **Dynamiczny motyw (Dzień/Noc):** Aplikacja automatycznie zmienia tło i kontrast czcionek w zależności od cyklu dobowego w wybranym mieście.
* **Rozszerzone statystyki:** Wyświetlanie nie tylko temperatury, ale również wilgotności, prędkości wiatru i ciśnienia atmosferycznego.
* **Rozbudowana obsługa błędów:** Bezpieczne zarządzanie kodami błędów HTTP (np. 404, 401) oraz problemami z połączeniem internetowym.
* **UX / Usability:** Obsługa wyszukiwania za pomocą klawisza `Enter` dla większej wygody użytkownika.

## 🛠️ Technologie
* **Python 3.x**
* **PyQt5** (Interfejs graficzny / CSS Styling)
* **Requests** (Komunikacja HTTP)
* **OpenWeatherMap API** (Źródło danych)

## 🔜 Roadmapa (Zrealizowane i przyszłe cele)
* [x] Stworzenie szkieletu GUI i podstawowa stylizacja (CSS).
* [x] Integracja z kluczem API oraz obsługa zapytań `requests`.
* [x] Wdrożenie obsługi błędów i weryfikacja danych wejściowych.
* [x] Implementacja dynamicznego motywu wizualnego.
* [ ] Zapisywanie ulubionych miejscowości (lokalny plik konfiguracyjny/JSON).
* [ ] Refaktoryzacja architektury kodu (separacja logiki API od widoku GUI).

## 💡 Inspiracja
Początkowa struktura interfejsu została zainspirowana kursem *Bro Code*, jednak projekt został znacząco rozbudowany o autorskie rozwiązania (np. obsługa błędów, dynamiczne motywy, dodatkowe statystyki), aby spełniać standardy nowoczesnych aplikacji desktopowych.

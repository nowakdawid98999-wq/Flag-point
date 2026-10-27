MTRVHS FLAG POINT — projekt Android
Producent: Błażej Lewna
Pakiet: com.mtrvhs.flagpoint
Wersja: 0.1.0

WAŻNE: To jest projekt źródłowy do zbudowania APK, a nie gotowy plik APK.
W środowisku, w którym utworzono ten pakiet, nie ma Android SDK ani Gradle,
więc nie dało się skompilować i podpisać instalatora APK.

Jak zbudować APK:
1. Zainstaluj Android Studio z oficjalnej strony developer.android.com/studio.
2. Rozpakuj MTRVHS_FLAG_POINT_Android.zip.
3. W Android Studio wybierz Open i wskaż folder MTRVHS_FLAG_POINT_Android.
4. Poczekaj na synchronizację Gradle i instalację wymaganych komponentów SDK.
5. Wybierz Build > Build APK(s).
6. Po zakończeniu wybierz Locate. APK debug zwykle pojawi się w:
   app/build/outputs/apk/debug/app-debug.apk

Co zawiera:
- ekran startowy, demonstracyjną mapę i kolorowe punkty
- formularz aktywności: spacery, zakupy, transport i wsparcie
- przykładowe profile społeczności
- ekran profilu i ustawień prywatności
- prośbę o lokalizację Androida dopiero po wybraniu funkcji lokalizacji
- brak wysyłania współrzędnych do serwera

Ograniczenia prototypu:
- profile i punkty są demonstracyjne
- brak prawdziwego backendu, rejestracji, czatu między urządzeniami i mapy dostawcy
- lokalizacja w WebView może zależeć od wersji Android System WebView; przed wydaniem
  należy przeprowadzić testy na urządzeniach
- to nie jest gotowy produkt medyczny ani system alarmowy

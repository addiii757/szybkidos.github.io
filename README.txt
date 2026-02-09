🎯 IP TRACKER DEMO - INSTRUKCJA URUCHOMIENIA

1. INSTALACJA BACKENDU:
   cd backend
   npm install
   
2. KONFIGURACJA MONGODB:
   - Załóż darmowe konto na MongoDB Atlas
   - Stwórz cluster
   - Pobierz connection string
   - Wklej do pliku backend/.env
   
3. URUCHOM BACKEND:
   cd backend
   npm start
   (lub npm run dev z nodemon)
   
4. URUCHOM FRONTEND:
   - Otwórz plik frontend/index.html w przeglądarce
   - Albo użyj Live Server w VS Code
   
5. DZIAŁANIE:
   - Zaznacz zgodę RODO
   - Kliknij "Pobierz moje IP"
   - Kliknij "Zapisz IP do bazy danych"
   - Sprawdź konsolę backendu (powinien pokazać zapis)

⚠️ UWAGA:
- To jest DEMO do nauki
- Nie używaj do zbierania prawdziwych danych bez zgody
- MongoDB Atlas ma darmową warstwę (512MB)

🔧 PROBLEMY:
- Backend nie działa? Sprawdź czy MongoDB jest połączone
- CORS error? Upewnij się że backend działa na localhost:3000
- Brak danych? Sprawdź konsolę przeglądarki (F12)
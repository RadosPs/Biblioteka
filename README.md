### **Opis projektu**
Celem projektu jest opracowanie aplikacji wspierającej pracowników biblioteki w zarządzaniu księgozbiorem. Aplikacja umożliwi sprawne administrowanie danymi dotyczącymi książek, kategorii, a także obsługę procesu wypożyczeń. System ma wspierać podstawowe operacje CRUD (Create, Read, Update, Delete) na danych oraz zapewnić intuicyjny interfejs użytkownika.

### **Wymagania niefunkcjonalne**
1. **Wydajność**: System powinien obsługiwać operacje na danych (dodawanie, usuwanie, modyfikowanie) bez opóźnień większych niż 2 sekundy dla pojedynczego zapytania.
2. **Skalowalność**: Aplikacja musi być zaprojektowana tak, aby umożliwić łatwą rozbudowę o dodatkowe funkcje w przyszłości.
3. **Bezpieczeństwo**: Dane dotyczące wypożyczeń i osób wypożyczających muszą być chronione zgodnie z RODO, a dostęp do aplikacji zabezpieczony autoryzacją użytkownika.
4. **Niezawodność**: Aplikacja musi działać stabilnie, zapewniając 99% dostępności w ciągu miesiąca.
5. **Przenośność**: System powinien działać na komputerach z systemem Windows z .NET Framework 6.0 lub wyższym.
6. **Łatwość utrzymania**: Kod aplikacji powinien być czytelny i dobrze udokumentowany, aby umożliwić jego utrzymanie przez przyszłych programistów.

### **Wymagania funkcjonalne**
1. **Zarządzanie kategoriami książek**:
   - Dodawanie nowych kategorii książek.
   - Edytowanie istniejących kategorii.
   - Usuwanie kategorii (z odpowiednim mechanizmem ostrzegania o przypisanych książkach).
2. **Zarządzanie książkami**:
   - Dodawanie książek z informacjami, takimi jak tytuł, autor, rok wydania, opis.
   - Edytowanie danych książek.
   - Usuwanie książek.
   - Przypisywanie książek do odpowiednich kategorii.
3. **Obsługa wypożyczeń**:
   - Rejestrowanie wypożyczenia książki, w tym danych o książce, osobie wypożyczającej (nazwisko, numer telefonu), dacie wypożyczenia i przewidywanej dacie zwrotu.
   - Aktualizacja informacji o zwrocie książki.
   - Możliwość przeglądania historii wypożyczeń.
4. **Interfejs użytkownika**:
   - Intuicyjny panel zarządzania księgozbiorem z dostępem do wymienionych funkcji.
   - Mechanizmy wyszukiwania i filtrowania książek oraz wypożyczeń.

### **Potencjalne ryzyka**
1. **Brak doświadczenia w tworzeniu baz danych w C#**:
   - Potrzebne będzie zapoznanie się z Entity Framework lub inną technologią ORM.
   - Możliwość wystąpienia opóźnień w implementacji.
2. **Nieznajomość technologii interfejsu użytkownika (np. WinForms, WPF)**:
   - Należy przeprowadzić szkolenia lub skorzystać z dostępnych tutoriali.
3. **Niedoszacowanie czasu potrzebnego na implementację funkcji związanych z bezpieczeństwem danych (np. szyfrowanie, walidacja danych)**.
4. **Brak dostatecznej dokumentacji projektu**:
   - Może to utrudnić dalszą rozbudowę i utrzymanie systemu.
5. **Nieprzewidziane problemy techniczne**:
   - Błędy w integracji między warstwą bazy danych a logiką aplikacji.
   - Konieczność debugowania i poprawiania kodu może wpłynąć na harmonogram projektu.

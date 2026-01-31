# 💻 WebStudio

### Projekt indywidualny GoIT fullstack developer course

WebStudio to strona internetowa firmy specjalizującej się w projektowaniu i wdrażaniu rozwiązań aplikacji internetowych oraz projektów graficznych. Zawiera trzy główne działy: _Agencja_, _Portfolio_ oraz _Kontakt_. Projekt został zbudowany z naciskiem na responsywność i zgodnie ze strategią Mobile First w celu poprawy doświadczeń użytkownika na urządzeniach mobilnych, poprawę pozycjonowania w wynikach wyszukiwania, szybsze ładowanie stron, elastyczność i skalowalność oraz minimalizację zbędnych elementów. Zastosowanie preprocesora SASS spowodowało większą zwięzłość i czytelność kodu, możliwość wprowadzenia zmiennych oraz obsługi zagnieżdżania oraz modularność.

## 🌐 Demo

Zobacz stronę online: [WebStudio](https://brzozanet.github.io/webstudio/)

## 🛠️ Użyte technologie

- **HTML5** (struktura strony)
- **CSS3** (stylowanie z wykorzystaniem metodologii BEM)
- **SASS** (preprocesor CSS dla lepszej organizacji stylów)
- **JavaScript** (interaktywność strony)
- **Flexbox** (elastyczny układ strony)
- **Figma** (projekt graficzny)
- **Git & GitHub** (kontrola wersji i hosting)

## 📁 Struktura projektu

```
webstudio/
├── css/              # Skompilowane pliki CSS
├── sass/             # Pliki źródłowe SASS
├── js/               # Skrypty JavaScript
├── images/           # Grafiki i zasoby
├── svg/              # Ikony i grafiki wektorowe
├── index.html        # Strona główna
└── portfolio.html    # Strona portfolio
```

## 📋 Dostępne strony

1. **Strona Główna** (`index.html`)

   - Prezentacja firmy
   - Sekcja usług
   - Zespół
   - Portfolio
   - Kontakt

2. **Portfolio** (`portfolio.html`)
   - Galeria projektów
   - Filtry kategorii
   - Szczegóły realizacji

## 📱 Responsywność

Strona jest w pełni responsywna i dostosowana do następujących breakpointów:

- Mobile: < 768px
- Tablet: 768px - 1199px
- Desktop: ≥ 1200px

## 🔍 SEO i Wydajność

- Zoptymalizowane obrazy
- Semantyczny HTML
- Szybkie ładowanie strony
- Mobile-first approach
- Dostępność (WCAG)

## 🚀 Jak Uruchomić lokalnie

1. Sklonuj repozytorium:

   ```bash
   git clone https://github.com/brzozanet/webstudio.git
   ```

2. Przejdź do katalogu projektu:

   ```bash
   cd webstudio
   ```

3. Zainstaluj zależności (jeśli używasz npm):

   ```bash
   npm install
   ```

4. Uruchom kompilator SASS (jeśli chcesz modyfikować style):

   ```bash
   npm run sass
   ```

5. Otwórz plik `index.html` w przeglądarce lub użyj lokalnego serwera (np. Live Server w VS Code)

Po uruchomieniu lokalnego serwera, strona będzie dostępna pod adresem:

- http://localhost:3000 (domyślny port dla większości lokalnych serwerów)
- http://127.0.0.1:3000

## 🌍 Wdrożenie

Projekt jest skonfigurowany do wdrożenia na GitHub Pages. Po zbudowaniu, strona będzie dostępna pod adresem:
`https://brzozanet.github.io/webstudio/`

## 📄 Licencja

Ten projekt jest udostępniony na licencji MIT. Szczegóły w pliku LICENSE.

<br>

![Screenshot App](https://raw.githubusercontent.com/brzozanet/webstudio/main/images/gh-cover-goit-markup.png)

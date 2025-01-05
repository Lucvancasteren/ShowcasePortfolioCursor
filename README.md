# React Terminal Interface met Commandosysteem en Videoachtergrond

Dit project is een React-component die een terminal-geïnspireerde interface biedt. De gebruiker kan commando's invoeren, een scrollbare tekstinterface gebruiken, een videoachtergrond bekijken en een menu openen. Het combineert interactieve functionaliteiten met een aantrekkelijke, minimalistische styling.

## Inhoudsopgave

- [Overzicht](#overzicht)
- [Kenmerken](#kenmerken)
- [Installatie](#installatie)
- [Gebruik](#gebruik)
- [Bestandsstructuur](#bestandsstructuur)
- [Aanpassingen](#aanpassingen)
- [Gebruikte Technologieën](#gebruikte-technologieën)
- [Licentie](#licentie)

---

## Overzicht

Dit project combineert verschillende interactieve functies, zoals een videoachtergrond, een zoekbalk voor commando's en een uitschuifbaar menu. Het biedt een unieke gebruikerservaring, geïnspireerd door terminals, met een focus op visuele aantrekkelijkheid en intuïtieve interacties.

---

## Kenmerken

- **Commandosysteem**:
  - Voer commando's in zoals `help`, `home`, `about`, enzovoort.
  - Geeft foutmeldingen als een commando onbekend is.
- **Videoachtergrond**:
  - Automatisch afspelende en doorlopende video op de achtergrond.
- **Scrollgedrag**:
  - Bijgehouden scrollpositie met React-hooks.
- **Uitschuifbaar menu**:
  - Open een menu via een knop, met opties zoals `home`, `about`, `projects`, enzovoort.
- **Reactieve UI**:
  - Dynamische statuslichten en altijd zichtbare tekst boven de video.
- **Responsive ontwerp**:
  - Geschikt voor verschillende schermgroottes en apparaten.

---

## Installatie

1. Clone de repository:
   ```bash
   git clone <repository-url>

2. Ga naar de projectmap:
   ```bash
   cd <project-map>

3. Installeer de vereiste afhankelijkheden:
   ```bash
   npm install

4. Start de ontwikkelserver
   ```bash
   npm run dev

Gebruik
Start het project door de server te draaien en open de browser.
Typ commando's zoals help in de zoekbalk en druk op Enter.
Klik op de knop rechtsboven om het menu te openen.
Scroll naar beneden om te zien hoe de interface reageert op de scrollpositie.

Bestandsstructuur 

src/
├── Home.js                # Hoofdbestand met de React-component en logica
├── styles.css             # CSS-styling voor de component
├── public/
│   ├── afbeeldingen/      # Map met assets, zoals video's
│       └── luc.mp4        # Videoachtergrond
└── App.js                 # Rootbestand van de applicatie

Gebruikte Technologieën
React: JavaScript-bibliotheek voor het bouwen van gebruikersinterfaces.
Lucide React: Iconenbibliotheek voor eenvoudige en stijlvolle iconen.
CSS: Styling van de gebruikersinterface.
HTML5 Video: Voor de videoachtergrond.

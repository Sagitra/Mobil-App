# FTS

En enkel Android-applikation som använder Jetpack Compose för att demonstrera ett klickräknargränssnitt och anpassad temadesign.

## Innehåll

- [Introduktion](#introduktion)
- [Funktioner](#funktioner)
- [Installation och användning](#installation-och-användning)
- [Kodstruktur](#kodstruktur)
- [Författare](#författare)

## Introduktion

Denna applikation visar grundläggande användning av **Jetpack Compose** för att bygga användargränssnitt. Den inkluderar:
- En klickräknare som spårar antal klick.
- Dynamisk ljus och mörk temaanpassning baserat på systeminställningar.

## Funktioner

- **Klickräknare**: Klicka på skärmen för att öka räknaren.
- **Temastöd**: Dynamisk anpassning av ljus och mörk design.
- **Förhandsvisning**: Användargränssnittet kan förhandsgranskas direkt i designläge.

## Installation och användning

1. **Krav**: 
   - Android Studio Flamingo eller senare.
   - Enhet med Android 8.0 (API 26) eller senare.

2. **Installation**:
   - Klona detta repository till din lokala maskin.
   - Öppna projektet i Android Studio.
   - Kör applikationen på en fysisk eller virtuell enhet.

3. **Användning**:
   - Starta appen.
   - Klicka var som helst på skärmen för att öka räknaren.

## Kodstruktur

### `MainActivity.kt`

- **Huvudaktivitet**:
  - Hanterar skärmens uppbyggnad och använder en **Scaffold** för layout.
  - Innehåller två composables: `Greeting` och `ClickCounter`.

- **Composable-funktioner**:
  - `Greeting`: Visar ett välkomstmeddelande.
  - `ClickCounter`: Hanterar klickräknaren och visar räknarens aktuella värde.

### `FTSTheme.kt`

- **Temahantering**:
  - Definierar ljusa och mörka färgscheman.
  - Stöder dynamiska färger på Android 12+ enheter.
  - Använder `MaterialTheme` för att tillämpa färgscheman och typografi.

## Författare

- **Författare**: Herman, Joaquin

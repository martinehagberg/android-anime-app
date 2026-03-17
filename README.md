# 📱 Anime App – Android Project

En Android-applikasjon utviklet som eksamensprosjekt i Android programmering (PGR112).  
Appen gir brukeren mulighet til å utforske anime, søke etter spesifikke serier, lagre favoritter og opprette egne anime-idéer.

---

## 🚀 Funksjonalitet

Appen består av fire hovedskjermer:

### 🔍 1. Utforsk anime
- Henter data fra JIKAN API
- Viser liste med anime (LazyColumn)
- Filtrering etter sjanger
- Utvidbar beskrivelse (Se mer / Se mindre)
- Legg til favoritter

### 🔎 2. Søk etter anime
- Søk etter anime via ID
- Viser detaljer (bilde, rating, episoder, sjanger)
- Feilhåndtering ved ugyldig ID
- Mulighet for å lagre som favoritt

### 💡 3. Egne anime-idéer
- Opprette, redigere og slette ideer (CRUD)
- Lagring lokalt med Room database
- Dialog ved sletting (AlertDialog)

### ⭐ 4. Favoritter
- Liste over lagrede favoritt-anime
- Sortering
- Sletting med bekreftelse
- Oppdateres automatisk

---

## 🛠 Teknologier

- Kotlin
- Jetpack Compose
- MVVM-arkitektur
- Retrofit (API-kall)
- Room (lokal database)
- Coil (bildehåndtering)
- StateFlow / Flow
- Material Design 3

---

## 🧠 Hva jeg har lært

Gjennom dette prosjektet har jeg lært:

- Hvordan strukturere en app med MVVM
- Håndtering av API-kall med Retrofit
- Lokal datalagring med Room
- Reaktiv UI med StateFlow og Jetpack Compose
- Navigasjon mellom skjermer i Android
- Hvordan bygge brukervennlige og dynamiske grensesnitt

---

## 👩‍💻 Min rolle

Dette var et gruppeprosjekt hvor jeg bidro med:
- UI-utvikling med Jetpack Compose
- Implementasjon av funksjonalitet
- Samarbeid rundt arkitektur og struktur

---

## 📸 Screenshots

*(legg inn bilder her hvis du vil – dette gjør repoet MYE bedre)*

---

## ⚙️ Hvordan kjøre prosjektet

1. Klon repoet:
```bash
git clone https://github.com/ditt-brukernavn/android-anime-app.git

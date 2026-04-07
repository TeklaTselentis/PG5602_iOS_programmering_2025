# PG5602_iOS_programmering_2025
PG5602 iOS programmering eksamen 2025

# Beacon — iOS App (PG5602 H2025)

En iOS-app for å utforske og lagre kafeer, hoteller og kafeer i nærheten.

## Oppsett

### 1. Klone prosjektet
```bash
git clone <repo-url>
```

### 2. Legg inn API-nøkkel
Appen bruker [Geoapify](https://www.geoapify.com) for stedssøk. Gratis API-nøkkel kreves.

```bash
cp Beacon/Services/Secrets.example.plist Beacon/Services/Secrets.plist
```

Åpne `Secrets.plist` og bytt ut `YOUR_API_KEY_HERE` med din Geoapify API-nøkkel.

### 3. Åpne i Xcode
Åpne `Beacon.xcodeproj` i Xcode og kjør appen på simulator eller enhet.

## Krav
- Xcode 15+
- iOS 17+


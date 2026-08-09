# Budowa AI Bezpieczeństwo - BauGuard AI# Projekt BHP

## Summary
Projekt kursowy o budowaniu AI – BauGuard AI to inteligentny system wykorzystujący konwolucyjne sieci neuronowe (CNN) do automatycznego wykrywania naruszeń przepisów BHP na placu budowy w czasie rzeczywistym.

## Background
- **Problem:** Wypadki na placu budowy wynikające z braku środków ochrony osobistej (np. kasków, kamizelek) lub wejścia w strefę pracy maszyn. Tradycyjne kontrole ludzkie bywają ograniczone na dużych obiektach.
- **Motywacja:** Zwiększenie bezpieczeństwa pracowników budowlanych poprzez cyfryzację i wykorzystanie monitoringu wizyjnego wspieranego przez AI.

## Data and AI Techniques
- **Dane:** Zbiór obrazów i strumieni wideo z placów budowy zawierający przykłady prawidłowego wyposażenia oraz naruszeń BHP.
- **Techniki:** Konwolucyjne sieci neuronowe (CNN) oraz modele detekcji obiektów (np. architektury typu YOLO/MobileNet).

## How it is used
System analizuje obraz z kamer przemysłowych na budowie. W przypadku wykrycia pracownika bez kasku lub w strefie niedozwolonej, automatycznie wysyła powiadomienie alertowe do kierownika budowy lub brygadzisty.

## What it does not solve
System wspiera, ale nie zastępuje w pełni ludzkiego inspektora BHP. Może też mieć ograniczenia widoczności w trudnych warunkach atmosferycznych (np. bardzo gęsta mgła).

## What next
W przyszłości planowana jest integracja systemu z elektronicznymi kontrolami dostępu na teren budowy oraz rozbudowa o monitorowanie pracy maszyn ciężkich.

## Acknowledgment
Projekt inspirowany realnymi wyzwaniami w branży budowlanej i zarządzaniu placem budowy. Stworzony z wykorzystaniem narzędzi Open Source.

# Diagram procesu aplikacji

```mermaid
flowchart TD
    START --> "Wczytaj opis projektu"
    "Wczytaj opis projektu" --> "Analiza wymagań"
    "Analiza wymagań" --> "Projekt architektury"
    "Projekt architektury" --> "Implementacja"
    "Implementacja" --> "Testy jednostkowe"
    "Testy jednostkowe" --> "Wdrożenie"
    "Wdrożenie" --> "Monitorowanie i utrzymanie"
    "Monitorowanie i utrzymanie" --> KONIEC

# Diagram procesu aplikacji

```mermaid
flowchart TD
    START(["START"])
    LOAD["Wczytaj opis projektu"]
    ANALYZE["Analiza wymagań"]
    DESIGN["Projekt architektury"]
    IMPLEMENT["Implementacja"]
    TESTS["Testy (jednostkowe)"]
    DEPLOY["Wdrożenie"]
    MONITOR["Monitorowanie i utrzymanie"]
    END(["KONIEC"])

    START --> LOAD --> ANALYZE --> DESIGN --> IMPLEMENT --> TESTS --> DEPLOY --> MONITOR --> END

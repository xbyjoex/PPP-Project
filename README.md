# **PPP-Project** (Power-Plant-Predictions)

This repository contains documentation and code developed as part of my bachelor’s thesis.

The project is divided into two main layers:
1. **Data Analysis and Forecast Modeling**: The first layer focuses on exploratory data analysis (EDA), feature engineering, and the development and deployment of a time-series forecasting model for solar power plants using weather data.
2. **Data Streaming and Anomaly Detection**: The second layer involves building a pipeline to stream simulated data from these power plants using AWS services for anomaly detection and predictive maintenance.

The primary focus of the bachelor’s thesis is on MLOps, particularly on how to deploy and manage such tasks in a production environment. Additionally, a proof of concept (PoC) will be implemented to demonstrate the feasibility of the proposed approaches.

---

# Commit Konventionen/Prefixes

1. WIP - Work in Progress
Verwendung: Für unfertige Änderungen, die noch nicht produktionsbereit sind.
Beispiel: WIP: Update API integration

2. feat - Feature
Verwendung: Einführung eines neuen Features.
Beispiel: feat: Add user authentication

3. fix - Bugfix
Verwendung: Behebung eines Fehlers.
Beispiel: fix: Resolve null pointer exception in login handler

4. refactor - Refactoring
Verwendung: Änderungen am Code, die dessen Verhalten nicht ändern (z. B. Verbesserung der Lesbarkeit oder Optimierung).
Beispiel: refactor: Simplify database query logic

5. chore - Routine-Aufgaben
Verwendung: Änderungen, die keine funktionalen Auswirkungen haben (z. B. Updates von Abhängigkeiten oder Änderungen an Konfigurationsdateien).
Beispiel: chore: Update ESLint configuration

6. docs - Dokumentation
Verwendung: Änderungen an der Dokumentation.
Beispiel: docs: Add installation instructions to README

7. test - Tests
Verwendung: Hinzufügen oder Anpassen von Tests.
Beispiel: test: Add unit tests for payment service

8. style - Code-Formatierung
Verwendung: Formatierungsänderungen (z. B. Whitespaces, Semikolons), die die Logik nicht betreffen.
Beispiel: style: Fix indentation in CSS file

9. perf - Performance
Verwendung: Änderungen zur Verbesserung der Leistung.
Beispiel: perf: Optimize image loading

10. ci - Continuous Integration
Verwendung: Änderungen an CI/CD-Konfigurationen oder Workflows.
Beispiel: ci: Add deployment step for staging

11. build - Build-System
Verwendung: Änderungen am Build-System (z. B. Webpack, Makefile, npm).
Beispiel: build: Update webpack to v5

12. revert - Rückgängig machen
Verwendung: Rücknahme eines früheren Commits.
Beispiel: revert: Revert "feat: Add user authentication"
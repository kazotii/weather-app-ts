<img width="1919" height="875" alt="image" src="https://github.com/user-attachments/assets/9eac69de-6bc6-4182-9fca-8a8cea300786" />
https://kazotii.github.io/weather-app-ts/

## Weather Dashboard (TypeScript)
Modern weather application built with React and TypeScript, focused on efficient state management and data persistence.

## Tech Stack
- **Core:** React, TypeScript, Vite
- **State Management:** Zustand + Middleware (Persist).
- **API:** Integration with weather data providers
- **Styling:** Dynamic CSS classes based on weather conditions (e.g., dynamic backgrounds).

## Features
- **Global State Management:** Powered by Zustand. Unlike standard useState patterns, this ensures a clean separation of business logic and UI.
- **State Persistence:** Implemented persist middleware to save user search history in localStorage. The application restores the last searched city even after a page refresh.
- **Asynchronous Data Handling:** Custom async logic using Fetch API with robust error handling (Try/Catch) and status checks.
- **Type Safety:** 100% written in TypeScript. Comprehensive WeatherData and WeatherStore interfaces ensure data integrity across the app.
- **Secure Environment:** API keys are managed via Vite environment variables (.env) to prevent sensitive data leaks.

## Architecture
The project follows a clean logic-component separation:
/functions: Centralized store and API logic.
/components: Pure UI components receiving data via selectors.

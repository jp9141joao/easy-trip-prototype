# Easy Trip (prototype)

Early mobile prototype of **Easy Trip**, the travel planning app I am building for my capstone project (TCC) in Software Engineering at Uni-FACEF.

This repository explores the app's home layout and visual design: travel content cards, ratings and safe image loading, built as a reusable component library.

## Tech stack

- React Native with Expo and Expo Router
- TypeScript
- React Navigation and React Native Reanimated
- Runs on Android, iOS and web (via React Native Web)

## Project structure

```
frontend/
  app/
    components/   buttons, cards, common and layout components
    constants/    colors and layout tokens
    data/         travel content used by the screens
    types/        TypeScript types for content
    utils/        rating helper and safe image component
```

## Running locally

```bash
cd frontend
npm install
npx expo start
```

Then open the app on an emulator, on a device with Expo Go, or in the browser (`npm run web`).

## Status

Prototype. The full Easy Trip application is developed in a separate private repository.

## Author

João Pedro Rosa de Paula: [LinkedIn](https://www.linkedin.com/in/joaopedrorosadepaula) · [GitHub](https://github.com/jp9141joao)

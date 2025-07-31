# WeatherApp 🌦

## How to Run the App

1. Clone the repository.
2. Open the project in **Android Studio Hedgehog or newer**.
3. Connect a device or start an emulator.
4. Run the app via `Run > Run 'app'` or use the green ▶️ button.

The app requires an Internet connection and an API key for OpenWeatherMap (already included via Constants.kt).
---

## Decisions and Trade-Offs

- Used **Jetpack Compose** for a modern declarative UI approach.
- Implemented **ViewModel + StateFlow** for lifecycle-safe UI state handling.
- Chose **manual test collection** (`toList()`, `advanceUntilIdle()`) over `Turbine`, since the testing style follows a more traditional coroutine-based approach.
- ViewModel restores the last searched city via `LocalStorage` using a simple flow instead of a more complex `DataStore` abstraction.

---

## What I'd Add With More Time

- Add UI tests using Jetpack Compose testing APIs.
- Build offline caching with Room for recent weather queries.
- Add location permission + fetch weather by GPS.
- Improve accessibility and design responsiveness.
- Switch to Kotlinx Serialization for full multiplatform support instead of Gson.

---

## 🧪 The Answer to 7/6

Original 20 decimal places of 7 ÷ 6:  
**1.16666666666666666666**

Modified as instructed (every other 6 → 4 starting from the 3rd 6, all else → Z):  
**Z.ZZZZ4Z4Z4Z4Z4Z4Z4Z4**


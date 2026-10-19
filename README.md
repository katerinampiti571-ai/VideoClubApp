**VideoClub** is an Android movie discovery application built with Kotlin and Jetpack Compose.This project was created as part of my journey as a Junior Android Developer, with a focus on learning modern Android development practices and building a complete application from UI to data layer.
Users can discover popular movies, search for movies, view movie details, and save their favorite movies.

**🎥 Demo**

https://github.com/user-attachments/assets/4804def0-ba5e-4bc6-be71-f82fa0cd8742

**✨ Features**

- 🎬 Browse popular movies
- 🔎 Search for movies
- 📄 View movie details
- ❤️ Add and remove favorite movies
- 📑 Pagination for loading movies
- 💾 Local movie storage with Room
- 📡 Offline access to cached data
- ⚠️ Error handling and retry functionality
  
**Home Screen**

<img width="1280" height="2856" alt="Screenshot_20261019_171519" src="https://github.com/user-attachments/assets/52f2c938-3603-4490-8f2b-3185399bfa86" />

**Search Screen**

<img width="1280" height="2856" alt="Screenshot_20261019_182724" src="https://github.com/user-attachments/assets/8ad48c5e-0c15-4c3a-92fe-dab0c5db985a" /> <img width="1280" height="2856" alt="Screenshot_20261019_183306" src="https://github.com/user-attachments/assets/4774bd6a-8377-45be-a576-bdc972215688" />

**Details Sceen**

<img width="1280" height="2856" alt="Screenshot_20261019_183430" src="https://github.com/user-attachments/assets/95a91017-c20f-43aa-9d63-af83deaf9582" />

**Favorites Screen**

<img width="1280" height="2856" alt="Screenshot_20261019_183804" src="https://github.com/user-attachments/assets/7861f7da-a5b8-495e-a964-61e3fb17fec4" />

**🛠️ Technologies**
- Kotlin
- Jetpack Compose
- Coroutines & Flow
- MVI
- Clean Architecture
- Retrofit
- Room
- Hilt
- Navigation Compose
- Kotlin Serialization
- JUnit
- MockK

**🏗️ Architecture**

The project follows **Clean Architecture**, separating the application into three main layers:

**Presentation**

Responsible for the UI and user interaction.
- Jetpack Compose
- ViewModels
- UI State
- StateFlow
- SharedFlow
- Navigation
  
**Domain**

Contains the application's business logic.
- Use Cases
- Repository interfaces
- Domain models
  
**Data**

Responsible for retrieving and storing data.
- Retrofit
- TMDB API
- Room
- Repository implementations
- DTOs and database entities
  
The application uses **MVI principles** for managing UI state and user interactions.

**🌐 API**

Movie information is provided by The Movie Database (TMDB) API.

🎨 UI Design
The application screens were designed in Figma and then implemented using Jetpack Compose.
🧪 Testing
The project includes unit tests for ViewModels using:
- JUnit
- MockK
- Kotlin Coroutines Test
Tests cover scenarios such as:
- UI state changes
- Pagination
- Navigation events
- Error handling
- Duplicate loading prevention


**VideoClub** is an Android movie discovery application built with **Kotlin** and **Jetpack Compose**. This project was created as part of my journey as a Junior Android Developer, with a focus on learning modern Android development practices and building a complete application from UI to data layer.
Users can discover popular movies, search for movies, view movie details, and save their favorite movies.

## Demo

https://github.com/user-attachments/assets/4804def0-ba5e-4bc6-be71-f82fa0cd8742

## Features

- Browse popular movies
- Search for movies
- View movie details
- Add and remove favorite movies
- Pagination for loading movies
- Local movie storage with Room
- Offline access to cached data
- Error handling and retry functionality
  
## Home Screen

Discover popular movies and browse through the latest movie collection.

<img width="300" height="669" alt="Screenshot_20261019_171519" src="https://github.com/user-attachments/assets/52f2c938-3603-4490-8f2b-3185399bfa86" /> <img width="300" height="669" alt="Screenshot 2026-10-19 at 8 05 48 PM" src="https://github.com/user-attachments/assets/5c48a954-c1cb-4617-ba6b-9237b64d0181" />

## Search Screen
Search for movies by title and quickly find the movie you're looking for.

<img width="300" height="669" alt="Screenshot_20261019_182724" src="https://github.com/user-attachments/assets/8ad48c5e-0c15-4c3a-92fe-dab0c5db985a" /> <img width="300" height="669" alt="Screenshot_20261019_183306" src="https://github.com/user-attachments/assets/4774bd6a-8377-45be-a576-bdc972215688" />

## Details Screen
View detailed information about a movie, including its title, rating, overview, date release and poster.

<img width="300" height="669" alt="Screenshot_20261019_183430" src="https://github.com/user-attachments/assets/95a91017-c20f-43aa-9d63-af83deaf9582" />

## Favorites Screen
View and manage the movies you have saved as favorites.

<img width="300" height="669" alt="Screenshot_20261019_195722" src="https://github.com/user-attachments/assets/7311b173-9cbb-4d32-889d-a7361577023d" /> <img width="300" height="669" alt="Screenshot 2026-10-19 at 7 54 25 PM" src="https://github.com/user-attachments/assets/dcd1288c-034a-45c5-9f89-b97a80db2acf" />

## Error handling

The app handles network errors and unexpected failures by displaying an appropriate error message and allowing the user to retry the request.

https://github.com/user-attachments/assets/46964b73-6aee-4fef-be1b-48ca91e69e36

## Technologies
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

## Architecture

The project follows **Clean Architecture**, separating the application into three main layers:

## Presentation

Responsible for the UI and user interaction.
- Jetpack Compose
- ViewModels
- UI State
- StateFlow
- SharedFlow
- Navigation
  
## Domain

Contains the application's business logic.
- Use Cases
- Repository interfaces
- Domain models
  
## Data

Responsible for retrieving and storing data.
- Retrofit
- TMDB API
- Room
- Repository implementations
- DTOs and database entities
  
The application uses **MVI principles** for managing UI state and user interactions.

## API

Movie information is provided by [The Movie Database TMDB API] (https://developer.themoviedb.org/docs/getting-started)

## UI Design

The application screens were designed in Figma and then implemented using Jetpack Compose.

<img width="500" height="347" alt="Screenshot 2026-10-19 at 8 49 43 PM" src="https://github.com/user-attachments/assets/e457443a-9a4d-49f3-af97-6c3f78a79cf6" />

## Testing
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

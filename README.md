# Fetch Hiring App

This Android application retrieves data from https://fetch-hiring.s3.amazonaws.com/hiring.json and displays it in an organized list.

## Features

- Retrieves data from the provided API endpoint
- Displays items grouped by "listId"
- Sorts results first by "listId", then by "name"
- Filters out items where "name" is blank or null
- Presents the data in an easy-to-read list

## Building and Running the App

1. Clone this repository or unzip the project files.
2. Open the project in Android Studio (version Hedgehog | 2023.1.1 or later).
3. Wait for Gradle to sync and download dependencies.
4. Connect an Android device or start an emulator.
5. Click the "Run" button (green triangle) in Android Studio.

## Technologies Used

- Kotlin
- Android Jetpack (ViewModel, LiveData)
- Retrofit for network requests
- Coroutines for asynchronous programming
- RecyclerView for efficient list display

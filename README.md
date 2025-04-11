# Suggester_Meal_App
Youtube Link: https://youtube.com/shorts/beb2nnkeg0g
GitHub Link: https://github.com/KholoAzi/Suggester_Meal_App

Project Report: Meal Suggester App

The Meal Suggester App is a dynamic Android application developed using Kotlin and Jetpack Compose within Android Studio Hedgehog (2023.1.1). The purpose of the app is to allow users to input a time of day and receive a relevant meal suggestion along with an image. When a user types “morning,” the app displays Oats and Berries as a breakfast option; when “lunch” is entered, it displays a Chicken Salad; and for “dinner,” it shows Fried Veggies. If a user enters any other time, an error message is presented to guide the user. The project highlights core Android development skills, including managing user input, implementing conditional logic, displaying images from local resources, and creating responsive user interfaces using Jetpack Compose.

The development process involved integrating user input fields, state management with `remember` and `mutableStateOf`, and conditional UI rendering using Kotlin's `if-else` logic. All images were placed in the app's `drawable` folder and referenced using `R.drawable.filename`, ensuring smooth image loading without the need for external resources. The app interface was built using Compose components such as `Column`, `Surface`, `TextField`, `Image`, and `Spacer`, offering a clean, modern UI structure.

Manual testing was conducted to validate the app's behavior, ensuring accurate display of meals and appropriate error messages for invalid entries. The app demonstrated strong responsiveness and visual consistency across different devices and screen sizes. Future improvements may include adding voice input, using image loading libraries like Coil for dynamic content, introducing favorite meal bookmarking, expanding the meal database, and implementing additional screens or animations.

This project provided valuable experience in Compose-based app development, including UI structuring, state handling, user validation, and integrating multimedia. The Meal Suggester App serves as a practical example of how to create engaging and functional Android applications with Jetpack Compose and Kotlin, offering both a foundation for future enhancements and a showcase of modern development practices.

Screenshoots: 




























References:

•	Google Developers, 2023. Jetpack Compose overview. [online] Available at: https://developer.android.com/jetpack/compose [Accessed 10 Apr. 2025].
•	Google Developers, 2023. Build your first Android app with Kotlin. [online] Available at: https://developer.android.com/kotlin [Accessed 10 Apr. 2025].
•	MindOrks, 2022. Kotlin for Android Developers: A practical guide. [online] Available at: https://blog.mindorks.com/kotlin-for-android-developers [Accessed 10 Apr. 2025].
•	Vogella, 2023. Android development with Kotlin and Jetpack Compose. [online] Available at: https://www.vogella.com/tutorials/AndroidJetpackCompose/article.html [Accessed 10 Apr. 2025].
•	Medium, 2023. Working with Images in Jetpack Compose. [online] Available at: https://medium.com/androiddevelopers/jetpack-compose-image-handling [Accessed 10 Apr. 2025].

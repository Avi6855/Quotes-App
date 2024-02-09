# Quotes-App

1. **Android SDK**: The entire project is developed using the Android Software Development Kit (SDK), which provides a set of development tools and libraries necessary for building Android applications.

2. **Android Support Library**: The app extends `AppCompatActivity` from the support library (`androidx.appcompat.app.AppCompatActivity`). This library provides backward compatibility for newer features on older versions of Android.

3. **SQLite Database**: The app utilizes SQLite, which is a lightweight relational database management system embedded in Android. It's used to store and manage favorite quotes locally on the device.

4. **Retrofit**: Retrofit is a type-safe HTTP client for Android and Java, used for making network requests. It simplifies the process of interacting with RESTful APIs by converting API calls into Java interfaces. In this app, Retrofit is used to fetch random quotes from the Quotable API (`https://api.quotable.io/`).

5. **Gson Converter**: Gson is a Java library used for serializing and deserializing Java objects to and from JSON. The GsonConverterFactory is used with Retrofit to convert JSON responses from the Quotable API into Java objects (QuoteResponse).

6. **Intents**: Intents are used to communicate between components in an Android app and to perform various actions such as opening activities, sharing content, etc. In this app, intents are used to open the developer's GitHub portfolio in a web browser and to share quotes via other apps.

7. **RecyclerView**: Although not explicitly mentioned in the code provided, it's likely that a RecyclerView is used to display the list of favorite quotes in the `ViewFavoritesActivity`. RecyclerView is a more flexible and efficient way to display lists of data compared to the older ListView.

8. **Toast**: Toasts are used to show simple feedback to the user in the form of a small pop-up message. In this app, Toasts are used to indicate success or failure when adding quotes to favorites.

9. **Material Design Components**: The app seems to adhere to the Material Design guidelines by using components like TextView, ImageView, LinearLayout, etc., with appropriate styling and layout.

10. **Java Programming Language**: The app is primarily written in Java, which is one of the official programming languages for Android app development.

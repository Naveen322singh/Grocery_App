Grocery App

Developed an Android application using Kotlin and XML in Android Studio to facilitate online grocery shopping. 
The app features a modern UI designed with Material Design principles, ensuring an intuitive and user-friendly experience. 
Utilized RecyclerView to efficiently display a dynamic list of grocery items, allowing users to scroll seamlessly through various categories. 
Implemented ViewHolder pattern for optimal performance and memory management. 
Integrated CardView to enhance the visual appeal of individual grocery items, providing users with detailed information and options to add items to their cart. 
Employed Intents for navigation between activities, including detailed item views and the shopping cart interface.

App Overview

The Grocery App is an Android application that allows users to browse and view a list of groceries, including their names and images. The app utilizes a RecyclerView to efficiently display the list of groceries.

Technical Requirements

Backend: The app uses Java to create a data model for the groceries, which includes the name and image URL for each item.
Frontend: The user interface is designed using XML, which includes a RecyclerView to display the list of groceries. Each item in the RecyclerView is represented by a custom layout that includes a TextView for the name and an ImageView for the image.
Data Storage: The app uses a local database (e.g., Room Persistence Library) to store the list of groceries, which can be pre-populated or fetched from a remote API.
Image Loading: The app uses a library such as Glide or Picasso to efficiently load and display the images for each grocery item.
Key Features

Efficient List Display: The RecyclerView is used to efficiently display the list of groceries, allowing for smooth scrolling and minimal memory usage.
Customizable Layout: The custom layout for each item in the RecyclerView can be easily modified to include additional information, such as prices or descriptions.
Image Caching: The image loading library is used to cache images, reducing the need for repeated network requests and improving app performance.

![Screenshot 2024-10-07 232548](https://github.com/user-attachments/assets/4c17aec0-a350-4006-83d6-a287193d466f)

![Screenshot 2024-10-07 232607](https://github.com/user-attachments/assets/6b831f18-caf7-4ca4-b383-682b075656af)

![Screenshot 2024-10-07 232625](https://github.com/user-attachments/assets/11c1a3ad-8db5-470d-9ae4-4ddb2394e962)




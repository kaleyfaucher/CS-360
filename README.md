# CS-360
Mobile Architecture and Programming

CS 360 Portfolio Artifact – Weight Tracking Mobile Application
App Overview and User Needs

The artifact submitted for this course is a fully functional Weight Tracking mobile application developed using Android Studio. The primary goal of the application is to allow users to securely log in and track their daily weight over time using a persistent local database. This app was designed to address user needs related to health monitoring, data persistence, and simplicity, ensuring users can easily record, view, update, and delete weight entries without unnecessary complexity. Optional SMS notification functionality was included to support user engagement while respecting user permission choices.

Screens, Features, and User-Centered UI Design

To support user needs, the application includes several essential screens and features:

A login and account creation screen allowing both new and returning users to access the app

A data grid screen that displays stored weight entries in a clear, organized format

CRUD functionality enabling users to create, read, update, and delete weight records

An SMS permission screen that prompts users for notification access while allowing the app to function normally if permission is denied

The UI was designed with clarity and accessibility in mind. Simple layouts, consistent navigation, and clear labels ensure users can intuitively interact with the app. These designs were successful because they minimized cognitive load, followed Android design conventions, and prioritized functionality over visual clutter.

Coding Approach and Development Strategy

The coding process was approached incrementally, with careful planning before implementation. Core functionality was developed first, followed by additional features such as database integration and permissions handling. The app was structured to separate concerns, using helper and repository classes to manage database interactions and user authentication logic. This modular approach improved readability, maintainability, and future scalability. These strategies can be applied to future projects by supporting easier debugging, feature expansion, and code reuse.

Testing and Validation

Testing was performed frequently using the Android Emulator to validate functionality at each stage of development. Login validation, database persistence, CRUD operations, and permission handling were tested independently and in combination. This process was critical in identifying logic errors, UI issues, and edge cases early, reducing the risk of larger failures later in development. Testing ensured the app behaved reliably under different user actions and permission responses.

Innovation and Problem Solving

One challenge encountered during development was managing persistent data storage while maintaining a clean and responsive UI. This was addressed by carefully integrating SQLite database operations with the app’s composable UI components. Another challenge involved implementing optional SMS functionality in a way that did not disrupt the app when permission was denied. This required thoughtful conditional logic and user feedback handling, reinforcing best practices for permission-based features.

Demonstrated Strengths and Successes

The component where I was most successful in demonstrating my skills was the database-driven functionality, particularly the integration of user authentication and weight data management using SQLite. This portion of the app highlights my ability to design persistent data systems, implement CRUD operations, and connect backend logic with a user-friendly interface. Overall, this project demonstrates my growth in mobile application development, user-centered design, and practical problem-solving.

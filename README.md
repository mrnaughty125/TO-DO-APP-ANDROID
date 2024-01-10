# ToDoListApp

ToDoList App is a demonstration of modern Android development techniques.

## Screenshots:
<div align="center">
  <img src="/screenshots/1.jpg" height="400px"/> <img src="/screenshots/2.jpg" height="400px"/> <img src="/screenshots/4.jpg" height="400px"/>
  <img src="/screenshots/5.jpg" height="400px"/> <img src="/screenshots/6.jpg" height="400px"/> <img src="/screenshots/7.jpg" height="400px"/>
</div>

## Project Description:

The ToDoList App is designed to showcase the power of modern Android development. It utilizes the following tech stack and open-source libraries:

### Tech Stack & Open-source Libraries:
- Minimum SDK level 26
- [Kotlin](https://kotlinlang.org/)
  - **Lifecycle:** Observe Android lifecycles and handle UI states upon the lifecycle changes.
  - **ViewModel:** Manages UI-related data holder and is lifecycle-aware. Allows data to survive configuration changes such as screen rotations.
  - **DataBinding:** Binds UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
  - **Room:** Constructs a Database by providing an abstraction layer over SQLite to allow fluent database access.
  - **Navigation Component Graphs:** To use single activity multiple fragment architecture.
- **Architecture:**
  - MVVM Architecture (View - DataBinding - ViewModel - Model)
  - Repository Pattern
- **Material-Components:** Material design components for building ripple animation, and CardView.
- **ColorPicker:** A simple Android color picker with a color wheel and lightness bar.

## How to Set Up and Run the Application:

Follow these steps to set up and run the ToDoList App:

1. Clone the repository: `git clone [repository-link]`
2. Open the project in Android Studio.
3. Build and run the app on an emulator or a physical device.

Feel free to explore the code, and if you have any feedback or suggestions, don't hesitate to reach out.

## Architecture:

**ToDoListApp**

![Architecture Diagram](figure/figure0.png)

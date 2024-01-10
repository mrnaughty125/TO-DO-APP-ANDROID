<h1>ToDoListApp</h1>


<p >  
ToDoList App demonstrates modern Android development 
</p>

# Screenshots:
<img src="/screenshots/1.jpg" height="400px"/> <img src="/screenshots/2.jpg" height="400px"/>
<img src="/screenshots/4.jpg" height="400px"/> 
<img src="/screenshots/5.jpg" height="400px"/> 
<img src="/screenshots/6.jpg" height="400px"/> <img src="/screenshots/7.jpg" height="400px"/>


## Tech stack & Open-source libraries
- Minimum SDK level 26
- [Kotlin](https://kotlinlang.org/)
  - Lifecycle: Observe Android lifecycles and handle UI states upon the lifecycle changes.
  - ViewModel: Manages UI-related data holder and lifecycle aware. Allows data to survive configuration changes such as screen rotations.
  - DataBinding: Binds UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
  - Room: Constructs Database by providing an abstraction layer over SQLite to allow fluent database access.
  - Navigation Component Graphs - To use single activity multiple fragment architecture.
- Architecture
  - MVVM Architecture (View - DataBinding - ViewModel - Model)
  - Repository Pattern
- Material-Components: Material design components for building ripple animation, and CardView.
- ColorPicker: Simple android color picker with color wheel and lightness bar.

## Architecture
**ToDoListApp** is based on the MVVM architecture and the Repository pattern, which follows the [Google's official architecture guidance](https://developer.android.com/topic/architecture).

![architecture](figure/figure0.png)



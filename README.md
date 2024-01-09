<h1>ToDoList</h1>



<p >  
ToDoList App demonstrates modern Android development with Hilt, Coroutines, LiveData, Jetpack (Room, ViewModel), and Material 3 Design based on MVVM architecture.

  I have done this with
  -organizing all the Categories with vibrant colors
  -quickly create and update tasks
  -organizing our life anytime and anywhere
  -always stay on track
</p>

# Screenshots:
![SS1](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/bb5988a4-dfa0-4bbe-97fb-976ac0245268) 
![SS2](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/570b49b9-8dba-4128-974e-38609fe8c6f5)
![SS3](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/ded02cef-51ba-4d85-ab9b-982f750688ed)
![SS4](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/67b4a4c4-6907-4ac9-aa7f-28a023a1fc5f)
![SS5](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/a79ec007-70a5-4f18-a299-0fdebdad35f6)
![SS7](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/2eaeda80-02ea-4ccb-884c-b8a32475270c)
![SS8](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/8594881d-6664-4c35-a59f-a6bcdee17434)
![SS9](https://github.com/MahitejVardhan/KEKAMVSR240016-MAHITEJ-TODOLIST/assets/133677337/d01e91ac-cae1-4d97-a3ae-d538fb096cd8)


## Open-source libraries
- Minimum SDK level 26
- [Kotlin](https://kotlinlang.org/)
  - Lifecycle: Observe Android lifecycles and handle UI states upon the lifecycle changes.
  - ViewModel: Manages UI-related data holder and lifecycle aware. Allows data to survive configuration changes such as screen rotations.
  - DataBinding: Binds UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
  - Room: Constructs Database by providing an abstraction layer over SQLite to allow fluent database access.
  - Navigation Component Graphs - To use single activity multiple fragment architecture.
  - [Hilt](https://dagger.dev/hilt/): For dependency injection.
  - [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) For asynchronous programming.
- Architecture
  - MVVM Architecture (View - DataBinding - ViewModel - Model)
  - Repository Pattern
- [Material-Components](https://github.com/material-components/material-components-android): Material design components for building ripple animation, and CardView.
- [ColorPicker](https://github.com/QuadFlask/colorpicker): Simple android color picker with color wheel and lightness bar.

## Architecture
**ToDoListApp** is based on the MVVM architecture and the Repository pattern, which follows the [Google's official architecture guidance](https://developer.android.com/topic/architecture).

![architecture](figure/figure0.png)

## Room Database Structure
![database structure](figure/RoomDBStructure.png)





# Notes app by using MVVM(ModelViewViewModel)
This is simple notes app that follows MVVM architectural design pattern and uses android jetpack components.

## MVVM Architecture

__MVVM__ - MVVM stands for Model, View, ViewModel. MVVM is one of the architectural patterns which enhances separation of concerns, it allows separating the user interface logic from the business (or the back-end) logic. Its target is to achieve the following principle “Keeping UI code simple and free of app logic in order to make it easier to manage”.      
 
 ## Screenshots
![152f0574-b510-4703-9ee0-1045fb786735](https://user-images.githubusercontent.com/56357841/131113467-6dfbbb00-5e61-432a-b00f-cde9b4544953.jpg)
![351de55a-b24a-45ac-902d-47b56ccdf6e8](https://user-images.githubusercontent.com/56357841/131117741-77648036-4496-43c7-a408-d2a4d23fbccc.jpg)
![dcaa9c38-7f9c-45cc-b7c4-1db8090f0da2](https://user-images.githubusercontent.com/56357841/131117795-1839851d-676f-43d7-b722-f1ef27423d25.jpg)
![e7c0115f-de02-40ca-abc1-ee0f5e34f729](https://user-images.githubusercontent.com/56357841/131117818-a10597e0-3d83-4b35-9d3f-26148e5e5223.jpg)
![ebdf521c-bd37-454f-ad0b-1d0760ddb88c](https://user-images.githubusercontent.com/56357841/131117840-fe7a80ae-112f-4617-bb1a-abcb46e8ba52.jpg)


## Android Jetpack components:-
1. __Navigation Components__ - Navigation component helps you implement navigation, from simple button clicks to more complex patterns, such as app bars and the navigation drawer. The Navigation component also ensures a consistent and predictable user experience by adhering to an established set of principles.

2. __Android Room Persistence__ - It is a SQLite object mapping library. Use it to Avoid boilerplate code and easily convert SQLite table data to Java objects. Room provides compile time checks of SQLite statements and can return RxJava, Flowable and LiveData observables.

3. __Kotlin Coroutines__ - A coroutine is a concurrency design pattern that you can use on Android to simplify code that executes asynchronously. On Android, coroutines help to manage long-running tasks that might otherwise block the main thread and cause your app to become unresponsive.

4. __ViewModel__ - It manages UI-related data in a lifecycle-conscious way. It stores UI-related data that isn't destroyed on app rotations.

5. __LiveData__ - It notifies views of any database changes. Use LiveData to build data objects that notify views when the underlying database changes.

6. __Kotlin__ - Kotlin is a modern statically typed programming language used by over 60% of professional Android developers that helps boost productivity, developer satisfaction, and code safety.

          It also uses RecyclerView with DiffUtill to improves overall app performances

## Features:-
1. Can save Note In a Local database
2.  Swipe To Delete
3.  Update
4. Colorful notes
5. Search for Notes created
7. RecyclerView Animations



## Libraries Used:-
   <h4>Library used</h4>
<ul>
<li><a href="https://developer.android.com/topic/libraries/architecture/room" target="_blank">Room</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/viewmodel" target="_blank">Viewmodel</a></li>
<li><a href="https://developer.android.com/guide/navigation/navigation-getting-started" target="_blank">Navigation Component</a></li>
<li><a href="https://developer.android.com/topic/libraries/architecture/livedata">Livedata</a></li>
<li><a href="https://developer.android.com/kotlin/coroutines" target="_blank">Coroutines</a></li>
<li><a href="https://material.io/develop/android/docs/getting-started/" target="_blank">Material library</a></li>          
   
</ul>


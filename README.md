# Notes app by using MVVM(ModelViewViewModel)
This is simple notes app that follows MVVM architectural design pattern and uses android jetpack components.

## MVVM Architecture

__MVVM__ - MVVM stands for Model, View, ViewModel. MVVM is one of the architectural patterns which enhances separation of concerns, it allows separating the user interface logic from the business (or the back-end) logic. Its target is to achieve the following principle “Keeping UI code simple and free of app logic in order to make it easier to manage”.      
 
 ## Screenshots
 
 <img src="https://camo.githubusercontent.com/..." data-canonical-src="https://user-images.githubusercontent.com/56357841/131119795-06a79b3f-fd6e-4fb4-b06f-93fcd0e57f52.jpg" width="250" height="350" />
 
![152f0574-b510-4703-9ee0-1045fb786735](https://user-images.githubusercontent.com/56357841/131119795-06a79b3f-fd6e-4fb4-b06f-93fcd0e57f52.jpg)
![351de55a-b24a-45ac-902d-47b56ccdf6e8](https://user-images.githubusercontent.com/56357841/131119825-e01d8215-e140-4247-a2cb-60f0a120ffde.jpg)
![dcaa9c38-7f9c-45cc-b7c4-1db8090f0da2](https://user-images.githubusercontent.com/56357841/131119836-09578b55-b296-473c-8850-678cb0233c58.jpg)
![e7c0115f-de02-40ca-abc1-ee0f5e34f729](https://user-images.githubusercontent.com/56357841/131119845-2a95bc23-db94-4485-91b4-d6e251d066e0.jpg)
![ebdf521c-bd37-454f-ad0b-1d0760ddb88c](https://user-images.githubusercontent.com/56357841/131119865-020d7157-33b8-4516-945d-b031141ca128.jpg)






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


# androidDependenciesList

```

// version codes
def room_version = "2.4.0"
def lifecycle_version = "2.4.0"
def coroutines_version = "1.5.2"
def nav_version = "2.4.1"


// Room Database

plugins {
    id 'kotlin-kapt'
}

implementation "androidx.room:room-runtime:$room_version"
kapt "androidx.room:room-compiler:$room_version"
implementation "androidx.room:room-ktx:$room_version"


// Coroutines

implementation "org.jetbrains.kotlinx:kotlinx-coroutines-android:$coroutines_version"
implementation "org.jetbrains.kotlinx:kotlinx-coroutines-core:$coroutines_version"

// ViewModel
implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:$lifecycle_version"


// LiveData
implementation "androidx.lifecycle:lifecycle-livedata-ktx:$lifecycle_version"

// navigation
implementation "androidx.navigation:navigation-fragment-ktx:$nav_version"
implementation "androidx.navigation:navigation-ui-ktx:$nav_version"


// navigtion safe args
// add in top level gradle file dependencies list
def nav_version = "2.4.1"
classpath "androidx.navigation:navigation-safe-args-gradle-plugin:$nav_version"
```

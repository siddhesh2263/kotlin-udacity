# Kotil App Development

* XML View Tags in activity_main.xml are loaded as View Objects in the MainActivity.kt by Layout Inflation.

* In order to make code more readable, `lateinit` property is used. This assures te Kotlin compiler that the variable will be initialised, before any function accesses the variabe, and avoid any null excpetions.

* Namespaces were used to support vector drawables for API level 21 and below. Since vector drawables are converted to png files by the gradle builder for lower end devices, it can cause lag issues.

in Kotlin, `val` is used to declare constants, while `var` is used to declare variables. 

You can infer type:
```
val myNum = 5
```
Or, you can specify type:
```
val myNum: Int = 5
```
---
`--` decrements while `++` increments. 

### Kotlin Switch Statements are Funky, but reasonable:
```
val day = 4
val result = when (day) {
  1 -> "Monday"
  2 -> "Tuesday"
  3 -> "Wednesday"
  4 -> "Thursday"
  5 -> "Friday"
  6 -> "Saturday"
  7 -> "Sunday"
  else -> "Invalid day."
}
println(result)
```
### Kotlin For-Loop:
```
val nums = arrayOf(1, 5, 10, 15, 20)
for (x in nums) {
  println(x)
}
```
### Kotlin Ranges!
```
fun main() {
  for (chars in 'a'..'x') {
    println(chars)
  }
}
```
### Kotlin Functions look like goofy Typescript:
```
fun myFunction(fname: String, age: Int): String {
  val message  = fname + " is " + age
  println(message)
  return message
}
```
### Function Shorthand (Like a typescript lambda with a `=` instead of a `=>`)
```dtd
fun myFunction(x: Int, y: Int) = x + y
```
### Simple Kotlin Class
```dtd
class Car {
  var brand = ""
  var model = ""
  var year = 0
}

// Create a c1 object of the Car class
val c1 = Car()

// Access the properties and add some values to it
c1.brand = "Ford"
c1.model = "Mustang"
c1.year = 1969

println(c1.brand)   // Outputs Ford
println(c1.model)   // Outputs Mustang
println(c1.year)    // Outputs 1969


```

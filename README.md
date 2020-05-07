# DataStructureInKotlin
Array | String | LinkedList | HashMap | One Dimension Array | Example 
## simple One Dimension Array 
```kotlin
private fun oneDimenArray(){
        val numArray = intArrayOf(12,4,23,54,67,87,62)
        for (i :Int in numArray)
            println("Array : $i")
    }//Output :: 12,4,23,54,67,87,62
```
## String
```kotlin
val firstName = "    Supriya"
        val lastName = "Bharti"
        val message = "i love my country"
        println("Full Name :: $firstName $lastName") //output : Supriya  Bharti
```
//print any Character by position
```kotlin
 println(firstName[0]) // Output : S
```
// Convert any string to UpperCase
```kotlin
println(lastName.toUpperCase()) // BHARTI
```
// remove all white space before and after sting 
```kotlin
println(firstName.trim()) // it will remove all the white space before staring
```
// split by space and keep in a List of String 
```kotlin
var splitMessage: List<String>
        splitMessage = message.split(" ")
        for (i: String in splitMessage)
            println(i)
```
## ArrayList<> | List<>
```kotlin
val dataList = ArrayList<String>() // define a Arraylist
        dataList.add("Supriya")
        dataList.add("India")
        dataList.add("USA") // added ={Supriya,India,USA}
```
```Kotlin
//replace any value bu position
        dataList[0] = "Hindustan"  // Output :- {Hindustan,India,USA}
```
```kotlin 
for (name :String in dataList) //itreate the list
            println("NAme are :: $name")
```


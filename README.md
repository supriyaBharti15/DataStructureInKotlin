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
```kotlin
/ iterate a list till a specific position
        for(pos:Int in 0 until 2)
            println("Data : ${dataList[pos]}  position :: $pos") //Output : Hindustan  position :: 0 ,  India  position :: 1
```
## HashMap | map
```kotlin
 val dataMap = HashMap<Int,String>() // declear the map
        dataMap.set(12,"India")
        dataMap.set(42,"Raja")
        dataMap.set(41,"supriya")
        dataMap.set(89,"ankit") // adding data to map
```
```kotlin
 for (data : String in dataMap.values)
            println("Value == $data") // it will print all map value
```
```kotlin
 for (data : Map.Entry<Int,String> in dataMap)
            println("Key == ${data.key} Value == ${data.value}") //Output == Key == 41 Value == supriya, Key == 89 Value == ankit,Key == 42 Value == Raja..

```

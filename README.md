# algo_cheatsheet
This repo is for keeping shorthand frequently used operations while solving algorithmic questions

# Collections


# Strings

### Erasing whitespaces
> str.trim().replace("\\\s+".toRegex(), " ")

### Iterating
> str.forEach { println(it) } //where it is char
  str.forEachIndexed { index: Int, c: Char -> 
  println(str[index] }
  
### Comparing
#### Compare chars
> fun compareTo(other: Char): Int
> Return difference between ASCII decimal values, 0 if equal

### Join to String CharArray/Array<Char>
> charArray.joinToString()
> String(charArray)
  
# Kotlin
### If statements
> If in kotlin is an expression, not a statement like in Java, so it is possible:
> val b: String = if (1 < 2) "yes" else "no"

### forEach and break/continue/return
> break doesn't work in forEach loop, works in for loop

### for loops
> for (item in collection) print(item)  
> for (i in 1..3) {
    println(i)
}  
> for (i in 6 downTo 0 step 2) {
    println(i)
}  
> for (i in array.indices) {
    println(array[i])
}  
> for ((index, value) in array.withIndex()) {
    println("the element at $index is $value")
}  

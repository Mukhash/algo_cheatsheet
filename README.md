# algo_cheatsheet
This repo is for keeping shorthand frequently used operations while solving algorithmic questions

# Strings

### Erasing whitespaces
> str.trim().replace("\\\s+".toRegex(), " ")

### Iterating
> str.forEach { println(it) } //where it is char
  str.forEachIndexed { index: Int, c: Char -> 
  println(str[index] }

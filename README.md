# Arrays Exit Ticket

Fork and clone this repo. On your fork, answer and commit the follow questions. When you are finished, submit the link to your repo on Canvas.


## Question 1

What will the code below print? Select one.

 ```swift
var sevenDwarfs = ["Grumpy", "Sleepy", "Sneezy", "Doc", "Bashful", "Dopey", "Happy"]

sevenDwarfs.remove(at: 0)
sevenDwarfs.remove(at: 1)
sevenDwarfs.remove(at: 2)

print(sevenDwarfs[3])
```

- Grumpy

- Sleepy

- Sneezy

- Doc

- Bashful

- Dopey

- Happy

- It will give an out-of-bounds error


## Question 2

What will the code below print? Select one.


```swift
var myArray: [Int] = [0]

for i in 0...10 where i % 3 == 0 {
    myArray.append(i)
}

var sum = 0

for number in myArray {
    sum += number
}

print(sum)
```


- 0

- 9

- 18

- 55

- It will give an error at compile-time

- It will give an error at run-time


## Question 3

Given the constants defined below, which of the following will print "Cheese"? Select one.

let dairy = ["Milk", "Yoghurt", "Cheese"]
let starch = ["Rice", "Bread", "Potato"]
let meat = ["Chicken", "Beef", "Lamb"]
let food = [dairy, starch, meat]

- `print(food[0][2])`

- `print(food[2][0])`

- `print(food[1][3])`

- `print(food[3][1])`


## Question 4

Given the constant `myArray`, which of the following code blocks will print the string "ABCDEF"?  Select all that apply.

`let myArray = ["Alpha", "Bravo", "Charlie", "Delta", "Echo", "Foxtrot"]`


A)
```swift
var stringA = ""

for element in myArray {
    stringA += String(element[element.characters.startIndex])
}

print(stringA)
```

B)
```swift
var stringB = ""

for element in myArray {
    stringB += element[0]
}

print(stringB)
```

C)
```swift
var stringC = "ABCDE"

for element in myArray {
    if element == "Foxtrot" {
        stringC += "F"
    }
}

print(stringC)
```

D)
```swift
var arrayD = ["A","B","C","D","E","F","G","H","I","J","K","L"]

for element in myArray {
    arrayD.remove(at: myArray.count)
}

var stringD = ""

for element in arrayD {
    stringD += element
}

print(stringD)
```

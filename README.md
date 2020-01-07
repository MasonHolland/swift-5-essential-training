# swift-5-essential-training

Compiled programming language that works with preexisting Objective-C modules and frameworks.

---

## Variables and Constants

- The `var` keyword declares a variable that can be changed at any time.
- The `let` keyword declares a variable as a constant, which cannot be changed after it's value is assigned
- camelCase is encouraged for Swift
- No line ending symbol


```
var currentHealth = 90
let maxHealth = 100

currentHealth = 13

var inventoryItems = 5, equipmentSlots = 3, currentGold = 42
```
---

## Type Safety and Inference

Swift is a __type safe__ language, meaning that every variable needs to have a specific type and a value that matches. Swift can also infer a variables type from it's assigned value, making variable declarations more concise.

```
// Type inference
var currentHealth = 90

// Type annotation
var characterName: String
characterName = "Guts"

// Type annotation and Inference
var maxHealth: Int = 100

// Multiple variables - type annotation shorthand
var inventoryItems, equipmentSlots, currentGold: Int
```
---

## Logging and Commenting

Commenting your code is the first step to keeping it clean and organized., and the `print` statement is your best friend when it comes to testing that your code is working as expected.

Single line comment = `//`

Multi line comment = `/* */`

```var antiHelloWorld = "We're not here..."
```

## String Interpolation

```
print("Hello \(2+3) World")
```

Anything between the characters `\()` will be interpolated into a string. 


# Operators
An operator is a symbols or keywords that performs operations on values and variables. They are fundamental for handling data, performing mathematical calculations, making comparisons and building the program logic.
## Operator types
### Arithmetic operators
Used to perform standard mathematical calculations.
* `+` Addition.
* `-` Subtraction.
* `*` Multiplication.
* `/` Division.
* `%` Modulo (Returns the remainder of a division).
* `//` Integer division.
* `**` Exponentiation.  
  
> 💡 **Note:** Modulo operator is commonly used to check if a number is even or odd (`num % 2 == 0`) or to determine if a number is a multiple of another.  

### Assignment operators
Used to assign or update a variable's value.

* **Simple assignment (`=`):** Assigns a value to a variable (*x = value*).
* **Addition assignment (`+=`):** Adds a value to the variable and assigns the result back to it (*x += value* is equivalent to *x = x + value*).
* **Subtraction assignment (`-=`):** Subtracts a value from the variable and assigns the result back to it (*x -= value* is equivalent to *x = x - value*).
* **Multiplication assignment (`*=`):** Multiplies the variable by a value and assigns the result back to it (*x *= value* is equivalent to *x = x * value*).
* **Division assignment (`/=`):** Divides the variable by a value and assigns the result back to it (*x /= value* is equivalent to *x = x / value*).
* **Modulo assignment (`%=`):** Takes the modulo of the variable and a value, then assigns the result back to it (*x %= value* is equivalent to *x = x % value*).

### Comparison operators
Comparison operators are fundamental in conditional structures (`if`/`else`) because they evaluate and return a boolean value (`True` or `False`).

* **Equal to (`==`):** Checks if two values are equal (*1 == 1* returns *True*).
* **Not equal to (`!=`):** Checks if two values are different (*1 != 1* returns *False*).
* **Greater than (`>`):** Checks if the left value is greater than the right value (*1 > 2* returns *False*).
* **Less than (`<`):** Checks if the left value is less than the right value (*1 < 2* returns *True*).
* **Greater than or equal to (`>=`):** Checks if the left value is greater than or equal to the right value (*1 >= 1* returns *True*).
* **Less than or equal to (`<=`):** Checks if the left value is less than or equal to the right value (*1 <= 1* returns *True*).

> 💡 **Note:** Many programming languages, such as JavaScript and TypeScript, feature a strict equality operator (`===`) and a strict inequality operator (`!==`). These operators compare both the value and the type, which helps prevent subtle bugs.

### Logical operators
Used to combine multiple conditions.
* **And** (`&&`): Returns `True` only if all conditions evaluate to `True`.
* **Or** (`||`): Returns `True` if at least one condition evaluates to `True`.
* **Not** (`!`): Inverts a boolean value. For example, `!True` evaluates to `False`.  
  
> 💡 **Note:** In Python, logical operators are written as keywords (`and`, `or`, and `not`) instead of symbols. The symbolic forms (`&&`, `||`, and `!`) are commonly used in languages such as Java, JavaScript, and TypeScript.

### Increment and decrement operators
These operators increase or decrease a variable's value by 1, and are commonly used in iterative constructs such as loops (*for*/*while*).
* **Increment (`++`):** Increases a variable's value by 1 (*x++* or *++x*).
* **Decrement (`--`):** Decreases a variable's value by 1 (*x--* or *--x*).
  
> 💡 **Note:** Python doesn't support these operators. Instead, increment and decrement are performed using the assignment operators `+=` and `-=`.

### Identity Operators
Used to check if two variables reference the exact same object in memory.
* **Is (`is`):** Evaluates to *True* if both variables point to the same object (*x is y*).
* **Is Not (`is not`):** Evaluates to *True* if the variables point to different objects (*x is not y*).

> 💡 **Note:** Do not confuse identity (`is`) with equality (`==`). While `==` checks whether two objects have the same value, `is` checks whether both variables refer to the exact same object.

### Membership Operators
Used to check if an element is present within a collection.
* **In (`in`):** Evaluates to *True* if the specified element is found in the collection (*x in list*).
* **Not In (`not in`):** Evaluates to *True* if the specified element isn't found in the collection (*x not in list*).
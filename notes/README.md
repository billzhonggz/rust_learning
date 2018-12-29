# Learning Notes

> Personal learning notes.

## Data Types

* For integer or float types, I need to specify the length of the variable.
  ```rust
  let hello:i32 = 1; //32-bit signed integer
  ```

## Functions

* Function with return value
  ```rust
  fn foo(x:i32) -> i32 {
      //Something
  }
  //Return type is written at the end.
  ```

## Control Flow

* Using `if` and `let` statements together.
  ```rust
  fn main() {
    let condition = true;
    let number = if condition {
        5
    } else {
        6
    }; // The expression returns 5 or 6 base on the value of "condition".
    println!("The value of number is: {}", number); //Output: 5
  }
  ```
  In this usage, the return type of all conditional sections should be same.

* Infinitive `loop`.

* `for` loop can be used like the way `for ... in ...`.

## Ownership

*To be continued.*
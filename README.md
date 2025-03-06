This is a Scientific Calculator written in Java. It allows users to input mathematical expressions and evaluates them using JavaScript's ScriptEngine.

Key Features:
Supports basic operations: +, -, *, /.
Includes advanced operations: exponentiation (^), modulus (%), and square root (sqrt(x)).
Users can input complex expressions, such as 5 + 3 * 2 ^ 3 - sqrt(16), and get the result.
The calculator evaluates the expression dynamically and displays the result.
The program allows for multiple calculations in one session until the user decides to exit.
How it Works:
The user enters a mathematical expression (e.g., 5 + 3 * 2 ^ 3).
The program replaces the ^ operator with Math.pow() and sqrt() with Math.sqrt().
The expression is then evaluated by the ScriptEngine and the result is shown.
The user is prompted if they want to perform another calculation.
This calculator is simple, flexible, and powerful for both basic and advanced mathematical operations.

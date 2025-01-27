# C# Learning Journey

## Today's Topics
- Comments in C#
- Basic Data Types
- Arithmetic Operators
- Type Conversion

## Comments in C#
C# supports three types of comments:

```csharp
// Single-line comment

/* Multi-line comment
that spans multiple lines */

/// XML documentation comment
/// Used for documenting methods and classes
```

## Basic Data Types
C# has several basic data types:

```csharp
int number = 42;          // Whole numbers
double price = 19.99;     // Decimal numbers
char grade = 'A';         // Single character
string name = "John";     // Text
bool isActive = true;     // Boolean (true/false)
```

Common numeric types and their ranges:
- `int`: -2,147,483,648 to 2,147,483,647
- `long`: -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
- `float`: ±1.5 × 10^-45 to ±3.4 × 10^38
- `double`: ±5.0 × 10^-324 to ±1.7 × 10^308

## Arithmetic Operators
Basic arithmetic operations in C#:

```csharp
int a = 10;
int b = 3;

int sum = a + b;      // Addition: 13
int diff = a - b;     // Subtraction: 7
int prod = a * b;     // Multiplication: 30
int quot = a / b;     // Division: 3
int rem = a % b;      // Modulus (remainder): 1
```

## Type Conversion
C# supports both implicit and explicit type conversion:

```csharp
// Implicit conversion (automatic)
int myInt = 100;
double myDouble = myInt;    // int to double

// Explicit conversion (casting)
double pi = 3.14;
int roundedPi = (int)pi;    // double to int

// Using Convert class
string numberStr = "123";
int parsedNumber = Convert.ToInt32(numberStr);

// Using Parse method
string decimalStr = "456.78";
double parsedDouble = double.Parse(decimalStr);
```

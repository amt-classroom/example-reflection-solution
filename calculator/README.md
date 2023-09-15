# Exercise 2: Calculator (Dynamic Proxy)

In the calculator module, the `Calculator` is an interface that defines the methods of a simple calculator.
The `BasicCalculator` class implements the `Calculator` interface and provides a basic implementation of the calculator.

Your task is to complete the `invoke` and `createProxy` methods of the `CalculatorHandler` class.
The `ìntercept` method of the `CalculatorHandler` class intercepts the method calls on a `Calculator` and logs the method calls and their arguments.
The `createProxy` method of the `CalculatorHandler` class creates a proxy for an implementation of the `Calculator` interface with the `CalculatorHandler` as invocation handler.

Executing the `main` method of the `CalculatorHandler` class should produce the following output:

```
Invoking method: add(1, 2)
Result of addition: 3
Invoking method: subtract(4, 2)
Result of subtraction: 2
```
# Test-driven Development

[<- Back](../README.md)

Test-Driven Development (TDD) is a software development methodology that
involves writing tests before writing the code that needs to be tested. This
document aims to provide best practices for implementing TDD.

## Why TDD?

- **Early Bug Detection**: Writing tests before the actual code helps in identifying issues early.
- **Simplified Debugging**: With tests already in place, debugging becomes easier.
- **Improved Design**: Often, TDD leads to better software design.
- **Code Confidence**: Tests act as a safety net, helping developers feel more confident when making changes to the code.

## TDD Workflow

The TDD process can be summarized by the "Red-Green-Refactor" loop:

1. **Red**: Write a failing test that defines a function or improvements of
     a function, which should fail initially because the function isn't
     implemented yet.

2. **Green**: Write the minimum amount of code necessary to pass the test.
     The key in this step is to write only as much code as necessary to make
     the test pass, no more.

3. **Refactor**: Clean up the code while keeping it functional. Refactoring
     is about making the code efficient, readable, or understandable without
     changing its behavior. The tests written should still pass after
     refactoring.

## Best Practices

### Writing Tests

1. **Descriptive Test Names**: Use descriptive names for your test cases to
     make it clear what each test covers.

2. **Arrange-Act-Assert**: Structure your test cases into the Arrange, Act,
     and Assert (AAA) format for readability and maintainability.

3. **One Assertion per Test**: Each test should represent one logical concept.
  
### Code Implementation

1. **Minimal Code**: Write only as much code as you need to pass the test.

2. **Incremental Steps**: Write tests and code in small increments to make it
     easier to pinpoint errors.

3. **Run All Tests**: After each change, run all tests to ensure that your
     new code didn't break any existing functionality.

### Refactoring

1. **Keep Tests Green**: Always ensure that your tests are passing after refactoring.
2. **Self-Contained**: Refactor in such a way that you don't introduce dependencies between tests.
3. **DRY (Don't Repeat Yourself)**: Remove any duplicated code.

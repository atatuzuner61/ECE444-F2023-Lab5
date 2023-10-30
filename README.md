# Lab5-TDD

Repo for Lab 5 submission

## Group Project Unit Test Contribution

My contribution to the group project tests is the 'test_invalid_get_event' function under flask-server/test/unit/test_event_service.py
Here is the link: [test_invalid_get_event](https://github.com/ECE444-2023Fall/project-1-web-application-design-group3-bugbusters/blob/ddd21c3277bd48429aeec76aa804a877f61b06a4/flask-server/test/unit/test_event_service.py#L33)

## Pros and Cons of TDD

Test-Driven Development (TDD) is a software development strategy where writing automated tests proceeds writing actual code.

### Pros:

1. **Code Quality:** TDD encourages developers to write clean, modular, and maintainable code. This often results in improved code quality and design.

2. **Faster Development:** TDD can accelerate the development process in the long run. It helps catch errors in code early in the development process, reducing time spent on debugging.

3. **Better Understanding of Requirements:** Writing tests first enables developers to understand the specific requirements more in-depth. It leads to more precise code implementation.

### Cons of TDD:

1. **Initial Time Investment:** Writing tests before the code can be time-consuming. This is the case especially for beginners or when dealing with complex systems. This initial investment might seem unattractive to some developers.

2. **Maintenance Overhead:** Maintaining tests alongside the codebase requires effort. As the application grows, so does the set of tests, which might demand additional time and resources.

3. **Difficulty in Legacy Systems:** Implementing TDD in an existing project or a legacy system can be challenging. Writing tests for code that wasn't designed for testability can produce complex situations.

4. **Not Guaranteed:** TDD doesn’t guarantee a bug-free or perfectly designed system. It provides sophisticated code with many details tested. However, it is up to the developer to make sure the test suite is complete and all bugs are accounted for with the tests.

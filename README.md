# ECE444-F2021-Lab6

Zeyuan Liu

this repo is based on https://github.com/mjhea0/flaskr-tdd.

## Test-Driven Development (TDD)

### Pros

Because I need to write a unit test each time to implemnt the actual codes, I'll tend to focus the architecture more, and make my codes to become more modular. For instance, for the education website, if I want to implement the comments and rating function of user, if writing codes first, I'd like to write all functions in a single route. However, when implementing test first, I'll tend to write a saperate comment router and rating router, to make the unit test simple and clear.

### Cons
The test itself needs to be maintained often, when the sturcture of the projects changes, the unit test will also change. In the meanwhile, writing tests take a lot of time, which will probably slow down the development. If the startup environments are in a rapid pace, there will be no time for developers to write the tests first.

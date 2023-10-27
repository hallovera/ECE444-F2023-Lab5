# ECE444-F2023-Lab5

Clone of repo: [https://github.com/mjhea0/flaskr-tdd](https://github.com/mjhea0/flaskr-tdd)

## Pros of Test-Driven Design

TDD helps improve code quality. Having the end requirements of a piece of code spelled out forces 
developers to consider edge cases and features that they otherwise would not have considered,
or would have ignored, if they hadn't thought about it beforehand.

TDD also makes debugging quicker. As each test case usually deals with a specific functionality,
when your code fails to pass it the developer will quickly know where the issues are coming from 
(e.g. if the login test case fails, the developer knows the login code is likely at fault) and so
will have to spend far less time trying to find the bugs, and more time solving the issue.

Finally, TDD helps improve documentation of the codebase. The tests, in a way, serve as documentation
in their own right, as comprehensive tests will describe what the code is supposed to do, and what the
expected results are. New developers can read the tests to figure out how the codebase works.

## Cons of Test-Driven Design

TDD is very time consuming. Between pre-determining what a functionality should do and/or output and 
writing the necessary code to test that, creating tests can require a lot of time and energy from 
developers, which can lead to developers becoming more frustrated and tired.

Also, TDD can increase the amount of codebase maintenance required. When the architecture is redesigned,
for instance, or when features are added/removed, new tests will have to be written to reflect the new
requirements, as tests in TDD must be written before any other coding takes place. This can dramatically
increase the maintenance required and make it add a lot of extra work whenever the codebase is refactored.

Finally, TDD may not be complete. If the test suite used is not comprehensive enough,
either because not enough tests are written or because the developers don't think of all the potential
edge cases, passing all the test cases will not mean that the code is working perfectly. The passing 
of the cases can lead to a false sense of security, making developers feel like they're done and don't
need to consider any more cases, and this can lead to issues down the line when the code is more heavily
used.

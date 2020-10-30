# ECE444-F2020-Lab6
## Group Project Unit Test
Here is the link to unit test I added to our project:  
https://github.com/ECE444-2020Fall/project1-webapp-group18-jimwaukees/blob/699f2b4e8f878fb7ab798de574883ee47de39d88/ui-react/src/App.test.js#L6 
  
## What are the pros and cons of TDD?
Test driven development (TDD) is a technique where tests are written and run prior to actually writing the corresponding code. The tests will initially fail and during development, the goal is to get them all to pass ensuring proper functionality and providing a sense of security because of the instant verification of correctness. As with any development methodology, TDD has its own pros and cons.  
### Pros
- Using a traditional method of developing code first and testing later often results in the testing taking less of a priority. Usually due to early deadlines and inaccurate estimates, tests are often overlooked or developed in haste leading to an unstable code base.
- Writing small sets tests first allows the developer to think of the code in a modular manner. A modular design pattern is often easier to understand and allows critical issues to surface earlier in the development process allowing them to be dealt with in a timely manner.
- Code with a thorough set of test cases replicates documentation allowing other team members to easily understand and modify that piece of software. This saves precious development time as it cuts down on the time others need to understand the code, regardless of how long ago it was written.
- Lastly, writing tests first allows the implementer to fully understand the requirements and acceptance criteria of thier task. Tests require the appropriate inputs and outputs to function properly so the programmer can fully grasp how the feature works.
### Cons
- The time to fully complete the feature grows drastically with TDD since writing tests is a prerequisite of actual development. This added time must be taken into consideration while estimating the time to complete pieces of software. Often deadlines are set on under-estimated stories causing programmers to rush.
- Some types of tests (ex. integration/e2e tests) are much harder to develop than simple unit tests and require a siginificant amount of time to set up and develop.
- Having an extensive test suite on your code base requires to be maintained. This is a task in and of itself as often there are third party dependencies used while testing.
- When migrating to a TDD framework, legacy code (code that already exists in the code base) has to be tested as well which is an incredibly challenging task.
- As you add more tests, the build gets longer since it is running more tests evertime it runs.
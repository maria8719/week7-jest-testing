## Jest

- Jest is a test runner (aka testing environment). It goes and runs your test.
- Jest is also a assertion library. It verifies that things are correct.
- Jest also does mocking (fake data or fake functions) for more inclusive tests.
- Jest also does snapshot testing (snapshot of code results)
- Jest uses Jasmine behind the scenes.

### Parcel and Jest

Parcel no longer uses Babel for it transpilation (uses SWC instead), but
Jest requires Babel, which is why it is installed.

Other examples of test runners and assertion libraries are:
 - Mocha: testing runner
 - Chai: assertion libary

### Running tests

When you type in your command line ```npm run test```, Jest will look for any .test file to run. If it cannot find any it will say "Your test suite must contain one test".

### Documentation

https://jestjs.io/docs/getting-started

https://jestjs.io/docs/api
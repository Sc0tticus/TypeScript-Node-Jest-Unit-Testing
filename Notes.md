Test Driver Development - TDD

-Write the Test first then write the code implementation.

Primitive Values = strings or numbers.

Unit Testing Hooks: points inside the testing workflow
where you can put additional functionality. beforeEach()
is a testing hook.

There are built in methods for describe() statement
like .skip and .only.

You can use .todo to skip an unfinished test and to send
you a reminder to finish it when you run the test suite.

	test.todo('test invalid URL')

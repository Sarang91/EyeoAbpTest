The solution for BlockingPage tests is designed using Selenium/Java using JUnit and Maven. I have used 'Jenkins' for CI setup.
The tests in the Automation Framework are designed using Page Object Model where I have add 'Pages' package for all the page classes 
(as of now, there's only one page class) and there's a package named 'tests' where I have placed the test class. The test class
'TestBlockingPage' contains all the test scenarios for BlockingPage. I have added a package called 'utility' where a properties file is there 
(with all required test data/links etc.) and a class to read those properties. Another class 'urlEncoder' is there as well which encodes the given
string into proper url format. Apart from that, there's BaseClass which instantiates the driver and has some common functionalities (waits as of now).
The solution can be implemented using any other tools/technologies/coding language, I chose Selenium since it's the most convenient one when we want Web/UI 
tests automation and Java was convenient as well. (We can also use Selenium with Python/C#). For CI setup, I have used 'Jenkins' where I gave my git 
repository link and triggering my tests from there. All the tests are passing and the code has been written cleanly.
The framework setup is very initial and this can be extended as and when needed and I believe there are improvement areas/scope as well but I tried 
implementing it as per basic need.

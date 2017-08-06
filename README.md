# Test
I used Selenium WebDriver Page Object Module to solve the test given. I used Maven project, TestNG and the programming language is Java.

The project was broken into layers.The browser package contains a base class where all the browsers were declared. It also contains a global.properties class where the browser type and application URL was entered.

I used Chrome browser to run the test and I pasted the Chrome Driver.exe file in the base class also.

You will find the page classes within the Browser package under the main folder.

The test can be run in one go by right clicking on the testNG.xml file within the project and clicking on 'run'

The Test Classes are within the TestCases Package in the test folder at the project level.

The Link to the Project/test can be found on my GitHub account through the following link: https://github.com/Muyiadesote/Test.git

Since I used POM, I used the concept of Inheritance. For each Test, he object were called from the corresponding page class.

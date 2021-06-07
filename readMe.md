Getting Started With Bobcat and LambdaTest
For this document, we provide example tests located in our Bobcat Github Repository.

Bobcat is framework dedicated to automated functional testing of web applications. It wraps Selenium, so anything possible in raw Selenium can be done with Bobcat. In this guide we will use Bobcat along with the Selenium Webdriver and the Java programming language.


You’ll need to use your Username and Authkey to run your tests on LambdaTest. 
You can find the required credentials here : https://www.lambdatest.com/capabilities-generator



Edit file ../src/main/resources/config.yaml with your USERNAME and ACCESS_KEY:

![image](https://user-images.githubusercontent.com/31619747/121085786-ec4d2a00-c7ff-11eb-9665-3f8c7bf00317.png)

Run the default test using the command:

gradlew clean test 

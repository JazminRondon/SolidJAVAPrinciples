# Unit Testing JUnit 5
#Annotation-always annotate every method for testing with @Test before it. 
asserSame will verify the two variable being compared are the same and point to same object in memory
reversal is asserNotSame
annonotation @BeforeAll will run before all tested method. @BeforeEach,@AfterAll @AfterEach are self explainatory 

#Single Responsibility Principle-A unit of code does only one thing, related to cohesion, separation of converns,
and i has one reason to change
To test target code- provide inputs to target code, validate outputs of target code, and verify target code fulfills
its single responsibility 
#Extraction-Separate concens by moving code. Code can move to new methods,classes,and function. 
Conservation, IDE supported extraction best for code that is not tested yet 

#Dependencies- code rarely works in isolation-code calls other code. Such dependencies may be application code or library code. Testing code that calls other code can be difficult:
-Side effects 
-Talks to remote services that are not always present.   
-Inconsistent behavior 

Test Driven Development-Rather than implementng a feature first, then testing it, drive development of
the feature from a test. Works by frequent switching from test to production code and back.
TBD keeps you focused on the task. They also produce easily testable designs. It helps produce clear interfaces 



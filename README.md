## Hi there 👋

- 🔭 I’m currently working on Software Testing and Test Automation of UI and API applications...
- 🌱 I’m currently learning Data Analytics and Data Science...
- 👯 I’m looking to collaborate on Data Analytics and Data Science Projects...
- 💬 Ask me about Software Testing and Test Automation...
- 📫 How to reach me: https://www.linkedin.com/in/sreeramgr/
- 😄 Pronouns: He/Him
- ⚡ Fun fact: Like to play chess and interested in Finance

# Automation Code Basics :
1. Make the class as final to avoid extending it
2. Create private constructor to avoid creating objects of that class
3. Create getter method to call any variables except constants
4. Make variable as static to use it without creating objects and private along with getter and setters
5. Create BaseTest for drivers setup() and teardown() and extend it with all classes
6. Use Owner for property, Lombak for POJO,AssertJ for assertions,Localdatejoda for date/time,Allure/Extent for reports
7. Always use trim() when reading any string values
8. Create page classes and By return type variables and make it as private final
9. Use method chaining so that we can access the methods in chains instead of calling objects always
10. Use By element so that dynamic xpath can be created which is not possible in pagefactory
11. Avoid using PageFactory may give stale element reference or Null pointer exception
12. Create enums and ExplicitWaitFactory for waits
13. Use Inheritance only if it satisfies IS A relationship and many methods of super class needs to used in subclass
14. Create ThreadLocal for driver instantiation of parallel execution

# Keyword Driven Framework
1. Create Action column in excel
2. Create Actions class and methods with same name in actions column
3. Create the Utility class that read the method names from Actions class and invoke it using Java Reflection API
4. When Action column name and action class method names matched the method will get invoked

# Data Driven Framework
1. Create the TestData column in excel
2. Create the DataProvider class and method that can read the data from excel for each testcase  - @DataProvider
3. Create the action methods that will read refer the data from dataprovider method  - @Test(dataProvider = "Above method name")

# Hybrid Framwork
1. Combination of both Keyword Driven and Data Driven
2. Create the Action and Test data column in excel
3. Create the Action class and DataProvider class and invoke them

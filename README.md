# staging-automation-primer-3-23
Repo for William training staging from 3/23 to 4/2.

# Training Goals
The main focus of this 2 week training is to prepare you for Automation interviews. Here are some of the topics we will cover:

1. Testing Overview
1. Quality Assurance
1. Testing Pyramid
1. Testing Lifecycle
1. Functional Testing
1. TDD - Test Driven Development
1. Test Strategy Document
1. Test Plan Document
1. Test Case Document
1. Requirements Traceability Matrix
1. Unit Testing
1. TestNG
1. BDD - Behavior Driven Development
1. Cucumber
1. Gherkin
1. System Testing
1. Selenium
1. WebDriver
1. Selenium Locators
1. Page Object Model
1. User Acceptance Testing
1. E2E testing
1. Jasmine and Protractor
1. Spring Testing


The goal is to be comfortable talking about any of these topics in the context of an interview

# Suggested projects

## Basic Backend with Spring, Testing documents and TDD
This is just a project to get our feet wet and get used to some traditional testing concepts
- Create a Kanban Board for your project
- Use Scrum
- Maintain Testing documents
- Use TDD
- get used to using JUnit and Mockito in the context of Spring Test

You can find the repo of the Spring Boot app we created using TDD [here](https://github.com/WilliamOna/chicken-restaurant-app)

## Java application with Servlets + JUnit+  Selenium + Cucumber + HTML/CSS/JS
Create a full stack app that uses the above technologies. The theme can be whatever you choose. It can be as simple or as complicated as you would like. For this project, the emphasis is more on the process you follow in constructing your application rather than what your application actually does. Doing the following will probably make you more successful in a future job interview:
- Create a Kanban Board for your project
- Use Scrum
- Maintain Testing documents: give filling out the test case document a shot as well as the RTM
- Use TDD and BDD
- Hit all of the levels of your testing pyramid

You can find the link to the project we did together here: [PirateApp](https://github.com/WilliamOna/2wPirateServer2.1/tree/dev). Make sure that you are looking in the `dev` branch

## TDD using Jasmine and Protractor in an Angular application.
Create a front end with Angular. Create the app using TDD with Jasmine. Also create E2E tests using protractor. You can see the project we did together here: [angular-ui](https://github.com/WilliamOna/angular-ui/tree/06-testing). Make sure that you are on the 06-testing branch.

# Where to go from here
Now that you have completed the primer, there are several other topics that I would recommend you look into, that we sort of skimmed over. Obviously you are not expected to do all of them. These are merely suggestions for those of you who want a little bit of guidance while going down certain rabbit hole. Take the time to do research on the following topics/subtopics if you can:
- Look into these other key terms for testing:
    - Defect vs Bug vs Feature
    - Defect Lifecycle
    - Some types of testing key terms:
        - Postive vs Negative testing
        - Alpha and Beta Testing
        - Performance testing: Testing how apps behave under certain conditions
            - ramp up vs ramp down testing
            - spike testing
            - stress testing vs load testing
        - exploratory testing
        - regression testing
        - retest
        - blackbox and whitebox testing
        - boundary analysis testing
        - functional vs nonfunctional testing
        - test automation
    - When you should automate vs when you should not automate?
- Other type of testing documentation:
    - Test policy
    - Defect report
    - Test Summary
    - etc.
- JUnit
    - how to set test priority
    - test case vs test suite
    - testing for exceptions occurring
- TestNG: kind of like JUnit but different
    - TestNG annotations vs JUnit annotations
    - Practice making test suites with TestNG
    - Using @DataProvider to do Data Driven tests
- Mockito without Spring
    - mocking
    - spying
    - when()
    - etc.
- Testing in Spring
    - How would you test a Repository layer?
    - Do you have to test models?
    - JSR 303/380 validation
- Selenium
    - Integrating Selenium into a Spring Boot application
    - Looking into using PageFactory
    - determining POM WebElement fields using annotations
    - Learn how to simulate more complex actions within Selenium
        - switching between tabs
        - dragging and dropping items
        - interacting with modals and alerts
        - etc.
    - absolute vs relative xpath
    - using waits in Selenium
        - implicit waits
        - explicit waits
        - why using Thread.sleep() is unideal
- Cucumber
    - try using a Scenario Outline with Examples
    - use tags to group scenarios
- Jasmine
    - Learn how to mock a service (especially one that is used to provide an observable that consumes an API)
    - Learn about spy-ing in jasmine
- Other tools for QA:
    - Sonar
        - Sonar Cloud vs Sonar Qube vs Sonar Lint
        - Try installing Sonar Lint into your IDE
        - Try integrating your Git Repo with Sonar Cloud or Sonar Qube maybe through Travis/CircleCI or even built in GitHub/GitLab integrations
    - RestAssured
        - used for API testing in Java
    - Postman/Newman
        - you can actually write tests and run them with postman. Worth Looking into if you are curious
    


# Appium Project

### **Project Creation**

Testinium supports java, gauge and cucumber frameworks in appium projects.

### **Appium-Gauge**

In projects created with **Appium-gauge**, what should be in the project;

* Projects created with Appium- Gauge must include unique tags to ensure proper test execution and reporting.
* Test scenarios should be written under the **spec file** to maintain the proper structure.
* The versions must be correctly specified in the **pom.xml** file;
*   **Gauge**: 0.11.1

    **Appium**: 7.0.0

    **Java**: 23

![](<../.gitbook/assets/image (33).png>)

-manifest.json file must contain xml report.

-The versions must be correctly specified in the **pom.xml** file (Java version is **23**).

![](<../.gitbook/assets/image (21).png>)

-gitignore file should be.

-Target file should not be pushed to remote repository.

-The hub url must be specified for the remote driver to work.

![](<../.gitbook/assets/image (62).png>)

### **Appium-Java**

In projects created with **Appium-Java**, what should be in the project

-gitignore file should be.

-Target file should not be pushed to remote repository

-The hub url must be specified for the remote driver to work.

-The versions must be correctly specified in the **pom.xml** file (Java version is **23**).

![](<../.gitbook/assets/image (27).png>)

### **Appium-Cucumber**

In projects created with **Appium-Cucumber**, what should be in the project;

-Feature files should be under src resources



![](../.gitbook/assets/image.png)

-gitignore file should be.

-Target file should not be pushed to remote repository .

-The hub url must be specified for the remote driver to work .

**Cucumber**: 7.20.1

**Java**: 23

![](<../.gitbook/assets/image (59).png>)

**Project Creation**

To create a Appium project, name the project, select Appium framework(java-gauge-cucumber). For example, the file type to work with Appium-gauge is selected.

It is indicated on the screen that it will be created as a maven project by default.

The repository link of the git account to which the source codes of the project will be sent is displayed.

A new project is created on the system by clicking the Save button.

![](<../.gitbook/assets/Ekran Resmi 2025-03-07 08.55.58.png>)

Then, the source code of the project should be sent to the link address of the git repository given in the system.

![](../.gitbook/assets/eeee.jpg)

### Scenario Creation

Click the create button on the all scenarios screen to create a scenario for the project.

![](<../.gitbook/assets/Ekran Resmi 2025-03-07 08.58.58.png>)

**1.Properties**

In order to create a scenario, we must first select the project from the **Select A Project** field on the screen that opens.

We give a name to the **Scenario Name** field for the scenario we will create.

**Description** is the field where comments about the Scenario are added.

**Group** is the area where you can group multiple scenarios under one group.

The **Maximum Execution Time** field is for selecting the maximum time the test should run. If a test continues to run up to this time limit, it will be aborted.

**2.Select Source File**

Select Source File is the area where your test files in the given repository are listed.

Allows you to select the test file you want\*\*.\*\*

**3.Select Test Methods**

Is the area where your test methods from the given test files are listed.

The scenario is created by selecting the desired test method or methods.

**Create Scenario Group**,allows you to select multiple test cases.

You can also **select all** your test cases with select all.

![](<../.gitbook/assets/Ekran Resmi 2025-03-07 09.05.18.png>)

It is the screen where the scenario steps in the spec file of the test method you selected are displayed.

It allows you to make and save the changes and edits you want in the test steps in your scenario.

![](<../.gitbook/assets/image (41).png>)

You can define necessary system parameters in this area.(Optional) Then you can use these parameters in your test code. Testinium will export these parameters to the system that will run the tests.

![](<../.gitbook/assets/Ekran Resmi 2025-03-07 09.06.41.png>)

### Plan Create

A plan should be created for the project and scenario created after the above processes.

You can create a new plan by clicking the **create** button on the "**all plan**" screen.

![](<../.gitbook/assets/Ekran Resmi 2025-03-07 09.13.35.png>)

Relevant fields are filled on the screen that opens.

**1.Properties**

**Select A Project**, \*\*\*\* is the area where the project selection for which the plan is to be created is made.

**Plan Name** is the field where you name the created plan.

**2.Scenarios**

Your scenarios are listed from the selected project. This is where you can select multiple scenarios to add a test plan.

**3.Scenario Order**

It allows you to sort among the selected scenarios. Scenarios are executed according to the selected order.

![](<../.gitbook/assets/image (66).png>)

**3.Platform Selection**

It offers the opportunity to run your scenarios on the platform you want.

For example, you can choose android operating system and asus as device, select mobile device Z00ED and version 6.0.1 and run your test on this platform.

You can save these selections with the add button by selecting a special device from the operating system, environment name, media version and optionally UDID section you have selected.

Your selected operating system, environment name, environment version and UDID information are displayed on the screen.

With the delete button, you can automatically delete the operating system, environment name, environment version and UDID.You can re-select and add.

With the save button, you can save your transactions and create your plan.

![](<../.gitbook/assets/image (61).png>)

After these processes, the project, scenario and plan that you will run in the testinium environment will be created.

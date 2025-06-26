<strong> **DO NOT DISTRIBUTE OR PUBLICLY POST SOLUTIONS TO THESE LABS. MAKE ALL FORKS OF THIS REPOSITORY WITH SOLUTION CODE PRIVATE. PLEASE REFER TO THE STUDENT CODE OF CONDUCT AND ETHICAL EXPECTATIONS FOR COLLEGE OF INFORMATION TECHNOLOGY STUDENTS FOR SPECIFICS. ** </strong>
# WESTERN GOVERNORS UNIVERSITY 
## D288 – BACK-END PROGRAMMING
Welcome to Back-End Programming! This is an opportunity for students to develop object-oriented applications that can be integrated with relational databases, write code for object-oriented applications using Spring framework, and implements design patterns for object-oriented applications. 
FOR SPECIFIC TASK INSTRUCTIONS AND REQUIREMENTS FOR THIS ASSESSMENT, PLEASE REFER TO THE COURSE PAGE.
## BASIC INSTRUCTIONS
For this project, you will be building your project using IntelliJ IDEA (Ultimate Edition) in a WGU-provided lab environment. You will be working with an existing MySQL database and Angular front-end, which are supplied for you in the lab environment. You will share this project to a private external GitLab repository and backup regularly. If you wish to work on it on your local machine, you will also need to download the Angular front-end application and create your own MySQL database. Use the links on your course page to install the integrated development environments (IDE), MySQL WorkBench, and IntelliJ IDEA, and pull the project from the lab environment.  


## SUPPLEMENTAL RESOURCES  
1.	How to clone a project to IntelliJ using Git?

> Ensure that you have Git installed on your system and that IntelliJ is installed using [Toolbox](https://www.jetbrains.com/toolbox-app/). Make sure that you are using version 2022.3.2. Once this has been confirmed, click the clone button and use the 'IntelliJ IDEA (HTTPS)' button. This will open IntelliJ with a prompt to clone the proejct. Save it in a safe location for the directory and press clone. IntelliJ will prompt you for your credentials. Enter in your WGU Credentials and the project will be cloned onto your local machine.  

2. How to create a branch and start Development?

- GitLab method
> Press the '+' button located near your branch name. In the dropdown list, press the 'New branch' button. This will allow you to create a name for your branch. Once the branch has been named, you can select 'Create Branch' to push the branch to your repository.

- IntelliJ method
> In IntelliJ, Go to the 'Git' button on the top toolbar. Select the new branch option and create a name for the branch. Make sure checkout branch is selected and press create. You can now add a commit message and push the new branch to the local repo.

## SUPPORT
If you need additional support, please navigate to the course page and reach out to your course instructor.
## FUTURE USE
Take this opportunity to create or add to a simple resume portfolio to highlight and showcase your work for future use in career search, experience, and education!


ntroduction
Throughout your career in software design and development, you will be asked to create, customize, and maintain applications with various features and functionality based on business requirements. For this assessment, you will create a Spring Framework Java back end for a web application using the solution statements provided in the requirements section of this assessment. The skills you showcase in your completed application will be useful in responding to technical interview questions for future employment. This application may also be added to your portfolio to show to future employers.

You will be building your project using IntelliJ IDEA (Ultimate Edition) in a WGU-provided lab environment in the LabFiles folder. You will be working with an existing MySQL database and Angular front end, which are supplied for you in the lab environment. You will share this project to your GitLab repository and backup regularly. Use the GitLab link in the web links section to create your Gitlab project in the WGU GitLab space, and prior to starting your work, reference the “GitLab How-To” web link to set up your project.

Note: Do not modify the given Angular front-end for this project.
Scenario
A travel agency has recently launched a complete overhaul of their front-end vacation bookings application using Angular and JavaScript. Lately, the front-end engineers have encountered various undocumented bugs when sending requests and fetching data from the back-end. Since the back-end was built in the early 1990s and the original developer has since retired and can no longer help troubleshoot, the existing team is concerned about the growing tech debt and lack of ongoing support. Your chief technology officer (CTO) decided to create a project to port over any mission-critical functionalities to a modern framework and has selected you, a software developer in Java, to start developing the minimally viable product (MVP) to migrate the legacy back-end to the modern Spring framework.
Requirements
Your submission must represent your original work and understanding of the course material. Most performance assessment submissions are automatically scanned through the WGU similarity checker. Students are strongly encouraged to wait for the similarity report to generate after uploading their work and then review it to ensure Academic Authenticity guidelines are met before submitting the file for evaluation. See Understanding Similarity Reports for more information.  

Grammarly Note: 
Professional Communication will be automatically assessed through Grammarly for Education in most performance assessments before a student submits work for evaluation. Students are strongly encouraged to review the Grammarly for Education feedback prior to submitting work for evaluation, as the overall submission will not pass without this aspect passing. See Use Grammarly for Education Effectively for more information.  

Microsoft Files Note: 
Write your paper in Microsoft Word (.doc or .docx) unless another Microsoft product, or pdf, is specified in the task directions. Tasks may not be submitted as cloud links, such as links to Google Docs, Google Slides, OneDrive, etc.  All supporting documentation, such as screenshots and proof of experience, should be collected in a pdf file and submitted separately from the main file. For more information, please see Computer System and Technology Requirements.  



You must use the rubric to direct the creation of your submission because it provides detailed criteria that will be used to evaluate your work. Each requirement below may be evaluated by more than one rubric aspect. The rubric aspect titles may contain hyperlinks to relevant portions of the course.



Note: External plugins and libraries other than those specified in this task are not allowed.


A.   Create a new Java project using Spring Initializr, with each of the following dependencies:

•    Spring Data JPA (spring-boot starter-data-jpa)

•    Rest Repositories (spring-boot-starter-data-rest)

•    MySQL Driver (mysql-connector-java)

•    Lombok



Note: Since the application properties will be empty, you will need to copy over the supplied application properties.



B.   Create your subgroup and project by logging into GitLab using the web link provided and do the following:

•    connect your new Java project

•    commit with a message and push when you complete each of the tasks listed below (parts B to F, etc.)



Note: Any submissions that do not have a commit after each task will not be evaluated.


Note: You may commit and push whenever you want to back up your changes, even if a task is not complete.


•    Submit a copy of the git repository URL and a copy of the repository branch history retrieved from your repository, which must include the commit messages and dates.


Note: Wait until you have completed all the following prompts before you create your copy of the repository branch history.



C.   Construct four new packages, one for each of the following: controllers, entities, dao, and services. The packages will need to be used for a checkout form and vacations packages list.


Note: The packages should be on the same level of the hierarchy.


Note: Construct a package named config and copy the RestDataConfig.java provided in the laboratory environment to the package. Modify it so that the package and imports have the correct package and import addresses. Copy the application.properties file that is provided in the laboratory environment into your application properties resource file.



D.   Write code for the entities package that includes entity classes and the enum designed to match the UML diagram.


E.   Write code for the dao package that includes repository interfaces for the entities that extend JpaRepository, and add cross-origin support.


F.   Write code for the services package that includes each of the following:

•    a purchase data class with a customer cart and a set of cart items

•    a purchase response data class that contains an order tracking number

•    a checkout service interface

•    a checkout service implementation class



G.   Write code to include validation to enforce the inputs needed by the Angular front-end.


H.   Write code for the controllers package that includes a REST controller checkout controller class with a post mapping to place orders.


Note: You do not need to duplicate REST functionality for each repository by creating methods in Java.


I.   Add five sample customers to the application programmatically.


Note: Make sure the customer information is not overwritten each time you run the application.


J.   Run your integrated application by adding a customer order for a vacation with two excursions using the unmodified Angular front-end. Provide screenshots for the following:

•    that your application does not generate a network error when adding the data

•    your database tables using MySQL Workbench to show the data was successfully added



Note: The screenshot should include the front-end view and the inspection console in the browser.


K.   Demonstrate professional communication in the content and presentation of your submission.

File Restrictions
File name may contain only letters, numbers, spaces, and these symbols: ! - _ . * ' ( )
File size limit: 200 MB
File types allowed: doc, docx, rtf, xls, xlsx, ppt, pptx, odt, pdf, csv, txt, qt, mov, mpg, avi, mp3, wav, mp4, wma, flv, asf, mpeg, wmv, m4v, svg, tif, tiff, jpeg, jpg, gif, png, zip, rar, tar, 7z
Rubric
A:SPRING INITIALIZR
Not Evident

A new Java project is not created using Spring Initializr.

Approaching Competence

The new Java project is created using Spring Initializr and includes all 4 of the listed dependencies, but the project does not run successfully or has errors.

Competent

The new Java project is successfully created using Spring Initializr and includes all 4 of the listed dependencies.

B:GIT REPOSITORY
Not Evident

A GitLab repository is not provided.

Approaching Competence

The subgroup and project are created in Gitlab, but the submission does not include all 3 of the listed requirements, or some of the requirements contain errors.

Competent

The subgroup and project are created in GitLab correctly and the submission includes all 3 of the listed requirements, and none of the requirements contain errors.

C:PACKAGE CONSTRUCTION
Not Evident

4 packages are not constructed.

Approaching Competence

4 new packages are constructed, but the submission is missing 1 or more of the 4 given packages, or the packages are not appropriate for a checkout form and vacations packages list.

Competent

4 new packages are accurately constructed, 1 for each of the 4 packages: controllers, entities, dao, and services. The packages are appropriate for a checkout form and vacations packages list.

D:ENITIES PACKAGE
Not Evident

The code is not provided for the entities package.

Approaching Competence

The code is provided for the entities package, but the code does not accurately represent the UML diagram. Or the code is not fully functional.

Competent

The code provided for the entities package includes entity classes designed to match the UML diagram. The code is fully functional.

E:REPOSITORIES PACKAGE
Not Evident

The code is not provided for the dao package.

Approaching Competence

The code is provided for the dao package, but the code is missing some repository interfaces for the entities that extend the JpaRepository or does not include any cross-origin support. Or the code is not fully functional.

Competent

The code provided for the dao package includes repository interfaces for the entities that extend the JpaRepository and adds cross-origin support. The code is fully functional.

F:SERVICES PACKAGE
Not Evident

The code is not provided for the services package.

Approaching Competence

The code is provided for the services package but does not include 1 or more of the 4 given parameters. Or the code is not fully functional.

Competent

The code provided for the services package includes all 4 of the given parameters. The code is fully functional.

G:VALIDATION
Not Evident

The code to include validation is not provided.

Approaching Competence

The code is provided to include validation but does not include all of the validation that is needed by the Angular front-end. Or the code is not fully functional.

Competent

The code provided includes all validation to enforce the inputs needed by the Angular front-end. The code is fully functional.

H:CONTROLLERS PACKAGE
Not Evident

The code is not provided for the controllers package.

Approaching Competence

The code is provided for the controllers package but does not include a REST controller checkout controller class. Or the class does not include a method with a post mapping to place orders. Or the code is not fully functional.

Competent

The code is provided for the controllers package and includes a REST controller checkout controller class with a post mapping to place orders. The code is fully functional.

I:ADD CUSTOMERS
Not Evident

No sample customers are added to the application.

Approaching Competence

Sample customers are added to the application, but fewer than five.

Competent

Five sample customers are added to the application. The sample data is added correctly.

J:RUN APPLICATION
Not Evident

The application does not run when adding a customer order for a vacation with 2 excursions.

Approaching Competence

The application runs when adding a customer order for a vacation with 2 excursions, but the application generates a network error when adding the data, does not save the data, or the Angular front-end was modified. Or the submission does not provide clear or complete screenshots, or 1 or both of the given requirements are incorrect.

Competent

The application runs successfully when adding a customer order for a vacation with 2 excursions while using the unmodified Angular front-end. Clear and complete screenshots are provided that show both given requirements were completed correctly.

K:PROFESSIONAL COMMUNICATION
Not Evident

This submission includes pervasive errors in professional communication related to grammar, sentence fluency, contextual spelling, or punctuation, negatively impacting the professional quality and clarity of the writing. Specific errors have been identified by Grammarly for Education under the Correctness category.   

Approaching Competence

This submission includes substantial errors in professional communication related to grammar, sentence fluency, contextual spelling, or punctuation. Specific errors have been identified by Grammarly for Education under the Correctness category.   

Competent

This submission includes satisfactory use of grammar, sentence fluency, contextual spelling, and punctuation, which promote accurate interpretation and understanding.  

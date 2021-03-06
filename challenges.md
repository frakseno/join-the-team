# About the Code Challenges
We have a couple of code challenges designed to give you the opportunity to showcase your skills. We love to see creativity, originality and simplicity of design. All of our projects involve some creativity, research, interest in data, automation and of course amazing instructions. Please make sure to write the most incredible and informative README.md files you can imagine.

There are tons of amazing open and free data sets to play with. Here are a few for inspiration:

* [Data.gov](https://www.data.gov/open-gov/)
* [NYC Open Data](https://nycopendata.socrata.com/)
* [Austin, TX Data](https://data.austintexas.gov/browse)
* [AWS Open Data](https://aws.amazon.com/public-data-sets/)
* [OpenData Baltimore](https://data.baltimorecity.gov/)
* [Open Data Sets on GitHub](http://www.kdnuggets.com/2015/04/awesome-public-datasets-github.html)
* [Firebase Data Sets](https://www.firebase.com/docs/open-data/)

# Project #1: For the Front-End Enthusiast and JavaScript Aficionados
We would like you to pick a couple of data sets from [OpenData Baltimore](https://data.baltimorecity.gov/) which can be combined into a single, shareable data set for visualization purposes.

Create a simple interactive single web page application that leverages the data set. The data can be reorganized however you like for storage purposes, as long as your code can successfully integrated or make use of the data. We would like this small web application to leverage a single web page framework, preferrably AngularJS. 

We are looking for you to design an interactive web application that visualizes the data. We recommend you present the data in a few formats visually via the combination of charts and grid controls. The application working with the data set must be capable of the following functional needs:

* Filtering the data
* Searching the data
* Sorting/Ordering the data (Grid Control)
* Interact with the visualization via a mouse (Visualization)

From a development perspective, we are looking for

* Your code should be DRY, maintainable and readable.
* Implement a front-end router.
* Code organization (Please no monolithic files)
* Handle client-side state.
* Include automated tests.
* 100% automated: Should be simple as a clone and a single command to run.

Make sure to provide an amazing README that tells us how to setup your project.

# Project #2: For the Java Full Stack Engineers
The goal of this assignment is to build a small web application that will demonstrate programming skills in Java (preferrably Spring MVC), building RESTful services, the build process, as well as front-end frameworks (preferrably AngularJS). You need to demonstrate an understanding of ORM (preferrably Hibernate) for persistence purposes with MySQL as your data store. We also want to see some basic test automation (Unit and Integration).

We would like you to pick a minimum of two data sets from [OpenData Baltimore](https://data.baltimorecity.gov/) which can be combined into a single, shareable data set in MySQL. The data sets should be selected carefully so that they share a foreign key relationship or two. We recommend that you design the schema and create automated scripts to easily bring the data into the database. This can be done via API calls to OpenData Baltimore, or simply package the data into a file as part of the Github project. 

We are looking for you to design an interactive web application that visualizes the data. We recommend you present the data in a few formats visually via the combination of charts and grid controls. The application working with the data set must be capable of the following functional needs:

* CRUD against the data (Create Read Update Delete): Provide a means for all (4) operations in the User Interface.
* Filtering the data
* Searching the data
* Sorting/Ordering the data (Grid Control)

From a development perspective, we are looking for:

* Your code should be DRY, maintainable and readable.
* Proper Code organization (Please no monolithic files).
* Organized relational data structure.
* Include automated tests.
* 100% automated: Should be simple as a clone and a few commands to run.

Make sure to provide an amazing README that tells us how to setup your project.

# Project #3: The Cloud Operations...Performance and Reliability

AirBnB has open sourced an really interesting and exciting data visualization platform called Caravel. Rather than have you build a visualization platform, we would like to see how well you can leverage an Open Source project. Your goal will be to customize the project by selecting an alternative data set. In addition, you will need to automate the provisioning, installation and setup of the project. No need to do any custom programming. We are hoping it is limited to adding a data set and automating. You really shouldn’t have to fork the project.

[Click Here for the Link](https://github.com/airbnb/caravel)

Identify a data set that would easily integrate with the Caravel application. (See their examples they use…try to find another data set that’s just as powerful as theirs)
Build the project so it’s up and running with your selected data set
Automate the project using a combination of Vagrant (virtualization purposes) and an automation language such as Ansible (provisioning purposes). Please use Ubuntu or Centos for the OS on Vagrant.
The work needs to be committed on Github with an appropriate README that anyone could follow in order to setup the application. Inclusion of code comments, tests, etc… are helpful as well.

The assignment involves identifying a data set that has multiple orientations/dimensions. It should have time-orientation, as well as other dimensions that would make the data exciting and fun to explore with a charting/visualization library. There are lots of data sets out there on the market to play around. Simple data sets that may look at population attributes, economic growth (GDP), literacy or health, etc…from a global perspective over time. There are other data sets that are security oriented such as [NVD](https://nvd.nist.gov/) or [CVE](https://cve.mitre.org/cve/). It does not have to be a security data set. It can be something completely different. The point is to find a data set to visualize in multiple dimensions or filters. Find a data set that is somewhat complex. 

# Project #4: Language Specialist (Agent Engineer)

Our agent technology is the heart and soul of our product. Agent engineers need to be highly proficient in the language they are supporting. They must want to explore the internals of the language and the engine the language runs within. 

As part of this project, we are looking for you to code the assignment from Project #2 for the Full Stack Engineer position. However, depending on the language you are looking to break into, we want you to use the specific framework and ORM listed below. For all languages the data should be stored in MySQL. We also recommend you use AngularJS for the SPA JavaScript effort. Note: you only have to pick one language!

| Language | framework                       | Use of ORM                |
|----------|---------------------------------|---------------------------|
| Java     | Spring                          | Hibernate                 |
| .Net     | .Net Web API with SPA Interface | ADO.Net                   |
| NodeJS   | ExpressJS                       | Sequelize                 |
| Ruby     | Rails                           | Active Record             |
| Python   | Django                          | Django ORM or SQL Alchemy |

What's unique about this project is that we are looking for you to perform some additional instrumentation/profiling on your own application. Each of the languages above provides an interface to capture a bevy of instrumentation from your web application. We want you to explore (2 out of 4) data points specifically:

* Time the request from start to finish.
* How much memory does a single page request take?
* How many strings were created for a single page request?
* How many assemblies/classes/methods were loaded (depends on language)?

Provide an interface that instruments the application to answer the questions above (preferrably both to console and log). Ideally, the interface is a flag or switch that can be turned on/off as part of the startup of the application. 

Make sure to provide an amazing README that tells us how to setup your project and turn on the instrumentation.


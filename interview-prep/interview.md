# INTERVIEW

\\

| Interview Prompts                                                                                                                                                                                                                                                                                                 | Topic                         | Objective                                                                                                         | 3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2                                                                                                                                                                                                                                                                                                                                                                                                                                               | 1                                                                                                                                                                                                                                                                                                                   | Relevant Links for students                                                                                                                                                                                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- | ----------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Change your browser width to a mobile (500px) setting. What were 2 things you did in your code to make it responsive to the change in width.](https://www.notion.so/Change-your-browser-width-to-a-mobile-500px-setting-What-were-2-things-you-did-in-your-code-to-m-5f0feadfb58b4e72972952cb02502834)           | Advanced CSS (responsiveness) | **Build modern responsive layouts for a wide range of screen sizes**                                              | Student can explain difference between max width in query and min width - min is mobile first (scale up), max width is desktop first (scale down). Student understands that viewport metatag needs to be in head for mobile browser to read media queries. Student consistently and appropriately uses responsive units (rem %, vh, vw) and can justify why and where they use them.                                                                                                                                                                                                | Student uses max width, min width, and responsive units correctly. Student understands basic principles of mobile first and desktop first design, but may not fully connect their code with these principles. Student's explanation presents no red flags as listed in requirements for a one.                                                                                                                                                  | Student is missing something important in media query such that switching browser width is problematic. Student cannot score higher than a one if they use pixels where they should use responsive unit or uses responsive units incorrectly.                                                                       | Review session on responsive CSS and accessibility: [https://www.youtube.com/watch?v=b3EsaDxuUl4](https://www.youtube.com/watch?v=b3EsaDxuUl4)                                                                                                                                                                                                |
| [Explain the importance of accessibility and how you would integrate that into websites or applications.](https://www.notion.so/Explain-the-importance-of-accessibility-and-how-you-would-integrate-that-into-websites-or-applicatio-fc29d2d53c4f4325adf1857fbafff433)                                            | Accessibility                 | Use HTML tags, CSS selectors, and Flexbox to build a responsive, accessible website                               | Student provides both examples (table) and non examples (div or span) of semantic html. Student can give examples of how semantic html tags are useful for any disadvantaged group (blind, low-connectivity areas). Student explains or attempts to explain how to make forms and images accessible and understands the importance of doing so. Student can explain why accessibility matters from both a business AND personal standpoint.                                                                                                                                         | Student can define semantic HTML as tags that have english meaning (may not use the term 'semantic HTML' and that's ok). Student similarly understands that semantic HTML is important for accessibility. Student can explain the use of alt tags for images, explains that structuring HTML is important Student can explain why accessibility matters from either a business OR personal standpoint.                                          | Student can't define semantic HTML. Student cannot score higher than a one if they can't or don't recognize accessibility as an important part of web development.                                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                               |
| [Find an example of a higher order function and a callback function in your project. Compare and contrast the two functions.](https://www.notion.so/Find-an-example-of-a-higher-order-function-and-a-callback-function-in-your-project-Compare-and-cont-97d05746039640bcad1204a28d7a1c36)                         | Intro to Javascript           | **Understand how to write and use functions and callbacks**                                                       | Code is logical and succinct. Student defines higher order function, callback functions and explains similarities between the two in terms of functionality and returns. Student can define callback as a function that can be passed into another function as a parameter and clearly distinguishes between an argument and a parameter.                                                                                                                                                                                                                                           | Student identifies the higher order function that takes three paramaters where at least one is a callback. Code does not need to be perfect to get a 2. Student can define callback as the function that gets passed into a higher order function and higher order function as recieving other functions as parameters.                                                                                                                         | Student cannot distinguish between higher order function and callbacks.                                                                                                                                                                                                                                             | Brit's class on this topic [https://www.youtube.com/watch?v=YPrDfOaG6W4\&amp=\&feature=youtu.be](https://www.youtube.com/watch?v=YPrDfOaG6W4\&amp=\&feature=youtu.be) and the codepen solution for that recording is here: [https://codepen.io/BritHemming/pen/LYVgjxg?editors=0010](https://codepen.io/BritHemming/pen/LYVgjxg?editors=0010) |
| [Show me in your Client-side App where you made an API call and how you retrieved the data from that call.](https://www.notion.so/Show-me-in-your-Client-side-App-where-you-made-an-API-call-and-how-you-retrieved-the-data-from-that--45e9b117b3274c0093175b562fbeeda3)                                          | Applied JS                    | **Build components to retrieve data from web APIs**                                                               | Student designed universally effective functions to handle promise and explains how they could be used with any API request. Data returned from the API was formatted to match the apps needs before it was set to state. Student may have used advanced JS syntax like async/await with try/catch blocks.                                                                                                                                                                                                                                                                          | Student explains how they used 'axios' or 'fetch' to access and return data from a specific endpoint (and understands, at a basic level, that an endpoint is where the data lives online). Student explains the use of .then() and .catch() to handle promise data                                                                                                                                                                              | Student may have an API call in their project, but cannot explain anything about the syntax or doesn't explain promises Student cannot score higher than a one if they are missing dependency argument (empty array) using the effect hook                                                                          | [https://learn.lambdaschool.com/web2/module/recKe8PW6ZMwjL1Qg/](https://learn.lambdaschool.com/web2/module/recKe8PW6ZMwjL1Qg/)                                                                                                                                                                                                                |
| [Where in your Client-side application did you implement route management? Explain the logic.](https://www.notion.so/Where-in-your-Client-side-application-did-you-implement-route-management-Explain-the-logic-96885efeb25f4a3898bf5b04777a4d8e)                                                                 | Single Page Apps              | **Use React Router and its components to render multiple routes**                                                 | Student's code is strategically organized at the component level with foresight to further development, proper usage of state and props are demonstrated throughout the project. Student can use and explain switch tags as important to force page to render one route at a time Not only are standard network request techniques employed, the code is organized in such a fashion that the student demonstrated proper use of container vs presentational components or other industry standards, conventions or patterns.                                                       | Student's code is organized at the component level, proper usage of state and props are demonstrated throughout the project, the Route management is properly installed and used to show top level pages as well as nested views where necessary Student uses the Route component to load pages based on path Student can make use of switch tags or exact prop, even if they don't exactly know why this is important                          | Student either doesn't have a routing system in place, or can't explain what routing is in a SPA application. Red flag: neglects to use browser router or router                                                                                                                                                    | [https://learn.lambdaschool.com/web2/module/recd7jGy7tfVkcFlX/](https://learn.lambdaschool.com/web2/module/recd7jGy7tfVkcFlX/)                                                                                                                                                                                                                |
| [In your client-side app, can you show a form component and explain how the state for the form is managed? Do you have form validation in place?](https://www.notion.so/In-your-client-side-app-can-you-show-a-form-component-and-explain-how-the-state-for-the-form-is-man-fe566cb0c5304e19bcdbe4723d7b3d01)     | Single Page Apps              | Use forms to build interactive Component Behavior.                                                                | Student showed great insight in setting up the state management for the app's forms. Form validation is in place for all fields, and covers all use cases. Loading states and success/error notifications are in place and add to the overall UX of the app Student performs CRUD operations on components in any capacity Open/save/exit/edit/cancel work how they should                                                                                                                                                                                                          | Student has set up component management for the forms in the app that makes sense for each form. Student made the decision to use a third-party library, like Formik, or not, and can defend their decision. Some form validation is in place.                                                                                                                                                                                                  | Student uses uncontrolled components, not controlled by react state. Student can't defend decision to use uncontrolled components. Performance of the app suffers due to improper form management.                                                                                                                  | [https://learn.lambdaschool.com/web2/sprint/recH2pYM3qVavZTRN](https://learn.lambdaschool.com/web2/sprint/recH2pYM3qVavZTRN)                                                                                                                                                                                                                  |
| [Explain your state management system and why you decided to use this system for state management.](https://www.notion.so/Explain-your-state-management-system-and-why-you-decided-to-use-this-system-for-state-management-b5cfb08bd4c543fe91b189ec6a5491fe)                                                      | State Management              | **Understand different ways to manage state and demonstrate appropropriate use of a state management system.**    | Student uses and explains state management that is coherent at all levels including explanation of the following details: - system has some global state (fetched a user) - every component has information about said global state Student can defend decision to handle state and component tree with redux, context, apollo-client, \*\*\*\* component state, or other researched thing over any other system. Student clearly understands both advantages and disadvantages of their decision. Student clearly explains how state is handled throughout levels of their system. | Student uses and explains state management that makes sense across component tree Student used redux, context, apollo-client, or component state and can point to advantages of using their chosen system in their context. Student does not have to use Redux or context - plain old React state management is fine as long as they can justify that decision. Student clearly explains how state is handled throughout levels of their system | Student may show use of a state management system but can't identify why they used it or any advantages of that system.                                                                                                                                                                                             | Review Session: [https://www.youtube.com/watch?v=iJBca\_uivG8](https://www.youtube.com/watch?v=iJBca\_uivG8) Training Kit: [https://learn.lambdaschool.com/web3/sprint/recukritK1B1pFrcM](https://learn.lambdaschool.com/web3/sprint/recukritK1B1pFrcM)                                                                                       |
| [Explain how you interact with an external data source/ service/ API and point to an example in your code.](https://www.notion.so/Explain-how-you-interact-with-an-external-data-source-service-API-and-point-to-an-example-in-your--3a65a3e2359b45d9bd705581d8264590)                                            | APIs                          | **Use RESTful HTTP methods to interact with an external data source.**                                            | Student meets requirements for a 2 and uses well organized file structure, dedicated files for accessing endpoints and demonstrates an in depth understanding of structure. Pages making HTTP requests do so in a logical manner that is cohesive with the app's state management system.                                                                                                                                                                                                                                                                                           | Student identifies external data sources as APIs and can find an appropriate and correct example of interaction in their code. Student is able to accurately defines 4 terms (CRUD) and knows why they used the operations they used. \[note: it is OK to ask students to define these if not in their first answer] - PUT replaces records - POST creates records - DELETE deletes records - GET fetches records                               | Student may or may not be able to identify APIs and explain that they are external data sources, but understanding of CRUD does not go beyond 'GET' requests.                                                                                                                                                       | Training Kit Link: [https://learn.lambdaschool.com/web3/module/recupVjaAKPqbuk7Y/](https://learn.lambdaschool.com/web3/module/recupVjaAKPqbuk7Y/)                                                                                                                                                                                             |
| [Can you show me an example where you defined unique routes for API resources? Why was it necessary to build your API this way?](https://www.notion.so/Can-you-show-me-an-example-where-you-defined-unique-routes-for-API-resources-Why-was-it-necessary-t-ba030773b8474881a8f396a5b3cfccdd)                      | Node.js                       | Use Express' built-in router to build and test a modular server API with Postman.                                 | Student's explanation includes variable scoping such that API could be dynamically deployed to any website. Student incorporated services interfaces and appropriate repositories for code reuse and deployed the API to a hosting platform. The API is configured to dynamically load configuration and secrets using environment variables                                                                                                                                                                                                                                        | Student built and deployed a Web API following the REST architectural pattern with code that is clean and organized using the Express Framework. Explanation must include differentiation between client and server route and why different routes are needed (specificity, readability) Student may include details about naming with nouns, http verb usage, resource hierarchy, etc.                                                         | Explanation includes only one route (either combines server and client, or only discusses one option). Explanation focuses on project requirements, does not actually explain the importance of routing. Student cannot score higher than a one if they misuse or incorrectly explain request and response methods. | Training Kit: [https://learn.lambdaschool.com/web4node/module/recBjiSulq0PYLCIj/](https://learn.lambdaschool.com/web4node/module/recBjiSulq0PYLCIj/)                                                                                                                                                                                          |
| [Describe your database organization in plain language. Include details about table schema, datatypes, constraints, and relationships between tables.](https://www.notion.so/Describe-your-database-organization-in-plain-language-Include-details-about-table-schema-datatypes-cc7f0570652e49b498e49284777a2ba9) | RDBMS                         | Use SQL to create and query a local database, table schemas, configure scripted schema migrations & seed scripts. | Student designs a highly detailed, scalable database. Student can relate design decisions to the "Normal Forms". Student migrated from SQLite3 to use a server RDBMS, like Postgres or MySQL and migrations and data access code continues to work without changes.                                                                                                                                                                                                                                                                                                                 | Student's explanation should focus on how database is interactive and easy to perform CRUD operations on. Student might discuss primary and foreign keys, how they manage different data types, how they manage different data relationships, etc. Student explains data persistence, normalized data models and explains how code ensures data integrity and consistency.                                                                      | Student cannot score higher than a one if they did not normalize data, did not join data, or did not use constraints (foreign keys) to guarantee data integrity.                                                                                                                                                    | Node: [https://learn.lambdaschool.com/web4node/sprint/receFLR7MpwQXesIN](https://learn.lambdaschool.com/web4node/sprint/receFLR7MpwQXesIN)                                                                                                                                                                                                    |
| [How did you handle token authentication in your client-side App?](https://www.notion.so/How-did-you-handle-token-authentication-in-your-client-side-App-5db5259232fe43e2a590025ae77d26c5)                                                                                                                        | Client-side authentication    | Handle authentication with tokens in a React app                                                                  | Student demonstrates tokens stored in cookies or explains why this would be a better strategy. Student explains client side treats token minimally and synchronization with server side. Student's app can clear tokens on logout but not close as to keep access channels open.                                                                                                                                                                                                                                                                                                    | Student explains that tokens are stored in either memory in browser, session storage or local storage and explains what that means for their application.                                                                                                                                                                                                                                                                                       | Student has a vague understanding of tokens and authentication. Student cannot score higher than a 1 if they only discuss server-side authentication                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                               |

#### Table of Contents

* Programming Languages/Frameworks/Platforms
  * Android
  * AngularJS
  * Angular
  * BackboneJS
  * C++
  * C
  * C♯
  * .NET
  * Clojure
  * CSS
  * Cucumber
  * Django
  * Docker
  * Elastic
  * EmberJS
  * Erlang
  * Golang
  * GraphQl
  * HTML
  * Ionic
  * iOS
  * Java
  * JavaScript
  * jQuery
  * Front-end build tools
  * KnockoutJS
  * Less
  * Lisp
  * NodeJS
  * Objective-C
  * PHP
  * Python
  * ReactJS
  * Rails
  * Ruby
  * Rust
  * Sass
  * Scala
  * Shell
  * Spark
  * Swift
  * Vue.js
  * Wordpress
  * TypeScript
* Database technologies
  * Cassandra
  * Microsoft Access
  * MongoDB
  * MySQL
  * Neo4j
  * Oracle
  * Postgres
  * SQL
  * SQL Lite
* Caching technologies
  * Memcached
  * Redis
* OS
  * Linux
  * Windows
* Algorithms
* Blockchain
* Coding exercises
* Comprehensive lists
* Design patterns
* Data structures
* Networks
* Security
* Data Science

### Programming Languages/Frameworks/Platforms

#### Android

* [10 Android interview question answers for Freshers](http://www.careerride.com/android-interview-questions.aspx)
* [20 Essential Android Interview Questions from Toptal](http://www.toptal.com/android/interview-questions)
* [25 Essential Android Interview Questions from Adeva](https://adevait.com/android/interview-questions)
* [A couple of Android questions posted by Quora users](https://www.quora.com/What-are-good-job-interview-questions-for-an-Android-developer)
* [A great list of Android interview questions covering all the aspects of this career](http://www.tutorialspoint.com/android/android\_interview\_questions.htm)
* [Collection of Android and Java related questions and topics, including general developer questions, Java core, Data structures, Build Tools, Programming Paradigms, Core Android, Databases and etc](https://github.com/derekargueta/Android-Interview-Questions)
* [Collection of Android and Java questions divided by experience](https://medium.com/@neteinstein/not-another-android-interviews-article-the-questions-3dedafa30bec)
* [RocketSkill App Android Interview Questions](https://github.com/mindash/android-structured-interview)
* [Android cheat sheet: Coding program, Data structure, Android and Java interview questions with answers and categorized by topics](https://github.com/anitaa1990/Android-Cheat-sheet)
* [Android Interview Questions And Answers From Beginner To Advanced](https://www.andreasschrade.com/2017/02/23/android-interview-questions/)
* [Interview Questions for Senior Android Developers](https://github.com/mohsenoid/Android-Interview-Questions)
* [35+ Android Interview Questions](https://www.interviewbit.com/android-interview-questions/)

#### AngularJS

* [12 Essential AngularJS Interview Questions from Toptal](http://www.toptal.com/angular-js/interview-questions)
* [An AngularJS exam with questions from beginner to expert by @gdi2290 from @AngularClass](https://github.com/gdi2290/ngExam)
* [29 AngularJS Interview Questions – Can You Answer Them All? Great Article from Codementor](https://www.codementor.io/angularjs/tutorial/angularjs-interview-questions-sample-answers)
* [AngularJS interview questions and answers for experienced developers](http://www.web-technology-experts-notes.in/2014/11/angularjs-interview-questions-and-answers-for-experienced.html)
* [AngularJS Interview Questions which have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of AngularJS](http://www.tutorialspoint.com/angularjs/angularjs\_interview\_questions.htm)
* [This article discusses the top 50 Most occurred AngularJS interview question with answers](http://www.codeproject.com/Articles/891718/AngularJS-Interview-Questions-and-Answers)
* [Top 25 Angularjs Interview Questions and Quiz](http://career.guru99.com/top-25-angular-js-interview-questions/)
* [100 AngularJS Interview Questions - Quick Refresher](https://www.techbeamers.com/latest-angularjs-interview-questions-answers/)

#### Angular

* [A list of helpful Angular related questions you can use to interview potential candidates, test yourself or completely ignore](https://github.com/Yonet/Angular-Interview-Questions)
* [Angular 2 Interview Questions](https://www.onlineinterviewquestions.com/angular2-interview-questions/)
* [List of 300 Angular Interview Questions and Answers](https://github.com/sudheerj/angular-interview-questions)
* [Angular Interview Questions (2020)](https://www.interviewbit.com/angular-interview-questions/)
* [Top Angular Interview Questions and Answers in 2021](https://hackr.io/blog/angular-interview-questions)

#### BackboneJS

* [8 Essential Backbonejs Interview Questions from Toptal](http://www.toptal.com/backbone-js/interview-questions)
* [Backbonejs Interview Questions And Answers from web technology experts notes](http://www.web-technology-experts-notes.in/2015/01/backbone-js-interview-questions-and-answers.html)
* [Top 25 Backbone.js interview questions](http://career.guru99.com/top-25-backbone-js-interview-questions/)

#### C++

* [1000+ Multiple Choice Questions & Answers in C++ with explanations](http://www.sanfoundry.com/cplusplus-interview-questions-answers/)
* [200 C++ interview questions and answers](http://www.careerride.com/C++-Interview-questions-Answer.aspx)
* [24 Essential C++ Interview Questions from Toptal](http://www.toptal.com/c-plus-plus/interview-questions)
* [C++ Interview Questions from GeekInterview](http://www.geekinterview.com/Interview-Questions/Languages/C-Plus-Plus)
* [C++ Programming Q\&A and quizzes from computer science portal for geeks](http://www.geeksforgeeks.org/c-plus-plus/)
* [C++ Programming Questions and Answers related to such topics as OOPs concepts, Object and Classes, Functions, Constructors and Destructors, Inheritance and etc](http://www.indiabix.com/cpp-programming/questions-and-answers/)
* [LeetCode Problems' Solutions written in C++](https://github.com/haoel/leetcode)

#### C

* [Basic C language technical frequently asked interview questions and answers It includes data structures, pointers interview questions and answers for experienced](http://www.cquestions.com/2010/10/c-interview-questions-and-answers.html)
* [C Programming Interview Questions and Answers for such topics as Bits and Bytes, Preprocessors, Functions, Strings, Language basics and etc](http://www.indiabix.com/technical/c/)
* [C Programming Interview Questions have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of C Programming](http://www.tutorialspoint.com/cprogramming/cprogramming\_interview\_questions.htm)
* [First set of commonly asked C programming interview questions from computer science portal for geeks](http://geeksquiz.com/commonly-asked-c-programming-interview-questions-set-1/)
* [Second set of commonly asked C programming interview questions from computer science portal for geeks](http://geeksquiz.com/commonly-asked-c-programming-interview-questions-set-2/)
* [9 Essential C Interview Questions with answers](https://www.toptal.com/c/interview-questions)
* [Top C Interview Questions and Answers](https://www.interviewbit.com/c-interview-questions/)

#### C\#

* [15 Essential C# Interview Question from Toptal](http://www.toptal.com/c-sharp/interview-questions)
* [C# interview questions from dotnetfunda.com](http://www.dotnetfunda.com/interviews/cat/6/csharp)
* [Top 50 C# Interview Questions & Answers](http://career.guru99.com/top-50-c-sharp-interview-questions-answers/)
* [50 C# Coding Interview Questions and Answers](https://www.techbeamers.com/csharp-coding-interview-questions-developers/)
* [20 C# OOPS Interview Questions and Answers](https://www.techbeamers.com/csharp-oops-interview-questions-answers/)
* [30+ C# Interview Questions](https://www.interviewbit.com/c-sharp-interview-questions/)

#### .NET

* [300 ASPNET interview questions and answers](http://www.careerride.com/ASPNet-Questions.aspx)
* [ASP.NET Core Interview Questions](https://www.talkingdotnet.com/asp-net-core-interview-questions/)
* [Great list of NET interview questions covering all the NET platform topics](http://www.indiabix.com/technical/dotnet/)
* [NET Interview Questions and Answers for Beginners which consists of the most frequently asked questions in NET This list of 100+ questions and answers gauge your familiarity with the NET platform](http://www.dotnetcurry.com/dotnetinterview/70/dotnet-interview-questions-answers-beginners)
* [Questions gathered by community of the StackOverflow](http://stackoverflow.com/questions/365489/questions-every-good-net-developer-should-be-able-to-answer)
* [What Great NET Developers Ought To Know (More NET Interview Questions)](http://www.hanselman.com/blog/WhatGreatNETDevelopersOughtToKnowMoreNETInterviewQuestions.aspx)

#### Clojure

* [Classic 'Fizz Buzz' interview question for Clojure developers](http://www.learningclojure.com/2014/05/fizz-buzz-interview-question.html)
* [Clojure Interview Questions for experienced devs](http://ita2zguide.blogspot.com.by/p/cc.html)
* [Coding exercises in Clojure, handy practice for technical interview questions](https://github.com/dpetrovics/coding-exercises)
* [Experience and questions from Clojure developer interview collected by Reddit users](https://www.reddit.com/r/Clojure/comments/34qhha/clojure\_coding\_job\_interview\_experience/)
* [Interview cake Clojure solutions](https://github.com/DerekCuevas/interview-cake-clj)

#### CSS

* [CSS interview questions and answers for freshers and experienced candidates Also there you can find CSS online practice tests to fight written tests and certification exams on CSS](http://www.careerride.com/Interview-Questions-CSS.aspx)
* [Development hiring managers and potential interviewees may find there sample CSS proficiency interview Q\&As and code snippets useful](http://www.techrepublic.com/blog/software-engineer/css-interview-questions-and-answers/)
* [Interview Questions and Exercises About CSS](https://css-tricks.com/interview-questions-css/)
* [Top 50 CSS(Cascading Style Sheet) Interview Questions covering the most of tricky CSS moments](http://career.guru99.com/top-50-csscascading-style-sheet-interview-questions/)
* [Front End Interview Handbook - CSS Questions and Answers](https://frontendinterviewhandbook.com/css-questions/)

#### Cucumber

* [Cucumber Web Application BDD Sample Interview Questions](https://ratedr05.wordpress.com/2017/09/22/cucumber-interview-questions/)
* [Guide to building a simple Cucumber + Watir page object pattern framework](http://watir.com/simple-cucumber-watir-page-object-pattern-framework/)

#### Django

* [Some abstract interview questions for Python/Django developers](http://insights.dice.com/2014/04/30/interview-questions-pythondjango-developers/)
* [Some Django basic interview questions to establish the basic level of the candidates](http://www.ilian.io/django-interview-questions/)
* [Top 16 Django Interview Questions for both freshers and experienced developers](http://career.guru99.com/top-16-django-interview-questions/)

#### Docker

* [Docker Interview Questions](https://mindmajix.com/docker-interview-questions)
* [Top Docker Interview Questions You Must Prepare In 2019](https://www.edureka.co/blog/interview-questions/docker-interview-questions/)
* [Top Docker Interview Questions And Answers](https://intellipaat.com/interview-question/docker-interview-questions/)
* [DOCKER (SOFTWARE) INTERVIEW QUESTIONS & ANSWERS](https://www.wisdomjobs.com/e-university/docker-software-interview-questions.html)
* [30 Docker Interview Questions and Answers in 2019](https://www.fullstack.cafe/blog/docker-interview-questions-and-answers)
* [Docker Interview Questions & Answers](https://www.interviewbit.com/docker-interview-questions/)
* [Top 50 Docker Interview Questions & Answers](https://www.wissenhive.com/blogs/top-50-docker-interview-questions-and-answers)
* [Top 50+ Docker Interview Questions and Answers in 2021](https://www.techgeekbuzz.com/top-docker-interview-questions/)

#### Elastic

* [Top Elastic Stack Interview Questions](https://logit.io/blog/post/the-top-50-elk-stack-and-elasticsearch-interview-questions)

#### EmberJS

* [8 Essential Emberjs Interview Questions from Toptal](http://www.toptal.com/emberjs/interview-questions)
* [Top 25 Emberjs Interview Questions for both freshers and experienced developers](http://career.guru99.com/top-25-ember-js-interview-questions/)

#### Erlang

* [Top 22 Erlang Interview Questions for both freshers and experienced developers](http://career.guru99.com/top-22-erlang-interview-questions/)

#### Golang

* [Solutions for Elements of Programming Interviews problems written in Golang](https://github.com/mrekucci/epi)
* [Solutions for some basic coding interview tasks written in Go](https://github.com/efischer19/golang\_ctci)
* [Top 20 GO Programming Interview Questions for both freshers and experienced developers](http://career.guru99.com/top-20-go-programming-interview-questions/)

#### GraphQl

* [8 GraphQl Interview Questions To Know](https://www.fullstack.cafe/blog/5-graphql-interview-questions-you-should-know)
* [How to GraphQl - Common Questions](https://www.howtographql.com/advanced/5-common-questions/)

#### HTML

* [10 Typical HTML Interview Exercises from SitePoint.com](http://www.sitepoint.com/10-typical-html-interview-exercises/)
* [16 Essential HTML5 Interview Questions from Toptal](http://www.toptal.com/html5/interview-questions)
* [40 important HTML 5 Interview questions with answers](http://www.codeproject.com/Articles/702051/important-HTML-Interview-questions-with-answe)
* [HTML interview questions and answers for freshers and experienced candidates Also find HTML online practice tests to fight written tests and certification exams on HTML](http://www.careerride.com/Interview-Questions-HTML.aspx)
* [Top 50 HTML Interview Questions for both freshers and experienced developers](http://career.guru99.com/top-50-html-interview-questions/)
* [Common HTML interview questions for freshers](http://www.javatpoint.com/html-interview-questions)
* [Front End Interview Handbook - HTML Questions and Answers](https://frontendinterviewhandbook.com/html-questions/)
* [30 HTML Interview Questions and Answers](https://www.techbeamers.com/latest-html-interview-questions/)
* [30+ HTML Interview Questions (2021)](https://www.interviewbit.com/html-interview-questions/)

#### Ionic

* [23 Beginner Level Ionic Framework Questions](http://www.codeandyou.com/p/ionic-interview-questions.html)
* [12 Essential Ionic Interview Questions](https://www.toptal.com/ionic/interview-questions)
* [45 Ionic Interview Questions](https://www.javatpoint.com/ionic-interview-questions)
* [Most Asked Ionic Interview Questions](https://www.maheshbhusanoor.com/article/ionic-interview-questions-answers.html)

#### iOS

* [14 Essential iOS Interview Questions from Toptal](http://www.toptal.com/ios/interview-questions)
* [20 iOS Developer Interview Questions and Answers for getting you ready for your interview](https://www.codementor.io/ios/tutorial/ios-interview-tips-questions-answers-objective-c)
* [25 Essential iOS Interview Questions from Adeva](https://adevait.com/ios/interview-questions)
* [A small guide to help those looking to hire a developer or designer for iOS work While tailored for iOS, many questions could be used for Android developers or designers as well A great self-test if you're looking to keep current or practice for your own interview](https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions)
* [All you need to know about iOS technical interview including some tips for preparing, questions and some coding exercises](http://www.raywenderlich.com/53962/ios-interview-questions)
* [Interview Questions for iOS and Mac Developers from the CEO of Black Pixel](https://blackpixel.com/writing/2013/04/interview-questions-for-ios-and-mac-developers-1.html)
* [iOS Interview Questions and Answers including such topics as Development Basics, App states and multitasking, App states, Core app objects](http://www.geekinterview.com/Interview-Questions/iOS)
* [iOS Interview Questions For Senior Developers](https://m.smartcloud.io/ios-interview-questions-for-senior-developers-in-2017-a94cc81c8205)
* [50 iOS Interview Questions And Answers 1](https://medium.com/ios-os-x-development/ios-interview-questions-13840247a57a)
* [50 iOS Interview Questions And Answers Part 2](https://medium.com/ios-os-x-development/50-ios-interview-questions-and-answers-part-2-45f952230b9f)
* [50 iOS Interview Questions And Answers Part 3](https://medium.com/ios-os-x-development/50-ios-interview-questions-and-answers-part-3-3fad146b6c3d)
* [50 iOS Interview Questions And Answers Part 4](https://medium.com/@duruldalkanat/50-ios-interview-questions-and-answers-part-4-6f26b26341a)
* [50 iOS Interview Questions And Answers Part 5](https://medium.com/@duruldalkanat/50-ios-interview-questions-and-answers-part-5-de6241374a8f)
* [10 iOS interview questions and answers](https://www.upwork.com/i/interview-questions/ios/)
* [iOS Developer and Designer Interview Questions](https://github.com/9magnets/iOS-Developer-and-Designer-Interview-Questions#tech)
* [IOS Interview Questions and Answers](http://www.thecrazyprogrammer.com/2015/11/ios-interview-questions-and-answers.html)
* [iOS Interview Questions For Beginners](http://ichuiphonedev.blogspot.com/2014/05/iphone-latest-interview-questions-and.html)
* [Babylon iOS Interview Questions](https://github.com/Babylonpartners/ios-playbook/blob/master/Interview/questions.md)
* [RocketSkill App iOS Interview Questions](https://github.com/mindash/iOS-structured-interview)
* [iOS Static vs Dynamic Dispatch](https://medium.com/flawless-app-stories/static-vs-dynamic-dispatch-in-swift-a-decisive-choice-cece1e872d)

#### Java

* [List of Java programs for interview Categoriwise](https://onurdesk.com/category/interview/interview-program-java/)
* [115 Java Interview Questions and Answers – The ULTIMATE List](http://www.javacodegeeks.com/2014/04/java-interview-questions-and-answers.html)
* [37 Java Interview Questions to Practice With from Codementor](https://www.codementor.io/java/tutorial/java-interview-sample-questions-answers)
* [21 Essential Java Interview Questions](http://www.toptal.com/java/interview-questions)
* [Top 30 Core Java Interview Questions](https://www.janbasktraining.com/blog/core-java-interview-questions-answers/)
* [29 Essential Java Interview Questions from Adeva](https://adevait.com/java/interview-questions)
* [A collection of Java interview questions and answers to them](https://github.com/svozniuk/java-interviews)
* [Data Structures and Algorithms in Java which can be useful in interview process](https://github.com/donbeave/interview)
* [Java Interview Questions: How to crack the TOP 15 questions](https://blog.udemy.com/java-interview-questions/)
* [300 Core Java Interview Questions](http://www.javatpoint.com/corejava-interview-questions)
* [Top 10 Tricky Java interview questions and Answers](http://java67.blogspot.com.by/2012/09/top-10-tricky-java-interview-questions-answers.html)
* [Top 25 Most Frequently Asked Interview Core Java Interview Questions And Answers](http://javahungry.blogspot.com/2013/06/top-25-most-frequently-asked-core-java.html)
* [Top 40 Core Java Interview Questions Answers from Telephonic Round](http://java67.blogspot.sg/2015/03/top-40-core-java-interview-questions-answers-telephonic-round.html)
* [Top 50 Spring Interview Questions You Must Prepare For In 2020](https://www.edureka.co/blog/interview-questions/spring-interview-questions/)
* [Spring Interview Questions And Answers](https://www.journaldev.com/2696/spring-interview-questions-and-answers)
* [Interview Cake Java Interview Questions](https://www.interviewcake.com/java-interview-questions)
* [Java Interview Questions & Quizzes](https://www.techbeamers.com/java-interview-questions/)
* [Essetial Java Interview Questions](https://fdk.codes/some-java-interview-questions/)
* [Fundamental Java Interview Questions](https://www.interviewbit.com/java-interview-questions/)

#### JavaScript

* [Practice common algorithms using JavaScript](https://github.com/ignacio-chiazzo/Algorithms-Leetcode-Javascript)
* [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
* [21 Essential JavaScript Interview Questions from best mentors all over the world](https://www.codementor.io/javascript/tutorial/21-essential-javascript-tech-interview-practice-questions-answers)
* [20 Essential JavaScript Interview Questions from Adeva](https://adevait.com/javascript-developers/interview-questions)
* [37 Essential JavaScript Interview Questions from Toptal](http://www.toptal.com/javascript/interview-questions)
* [5 More JavaScript Interview Exercises](http://www.sitepoint.com/5-javascript-interview-exercises/)
* [5 Typical JavaScript Interview Exercises](http://www.sitepoint.com/5-typical-javascript-interview-exercises/)
* [Development hiring managers and potential interviewees may find these sample JavaScript proficiency interview Q\&As and code snippets useful](http://www.techrepublic.com/blog/software-engineer/javascript-interview-questions-and-answers/)
* [123 Essential JavaScript Interview Question](https://github.com/nishant8BITS/123-Essential-JavaScript-Interview-Question)
* [JavaScript Interview Questions have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of JavaScript](http://www.tutorialspoint.com/javascript/javascript\_interview\_questions.htm)
* [JS: Basics and Tricky Questions](http://www.thatjsdude.com/interview/js2.html)
* [JS: Interview Algorithm](http://thatjsdude.com/interview/js1.html)
* [Some basic javascript coding challenges and interview questions](https://github.com/kolodny/exercises)
* [Some JavaScript interview exercises](https://github.com/csvenja/javascript-exercises)
* [Ten Questions I've Been Asked, Most More Than Once, Over Six Technical JavaScript / Front-End Engineer Job Interviews.](https://www.reddit.com/r/javascript/comments/3rb88w/ten\_questions\_ive\_been\_asked\_most\_more\_than\_once)
* [Top 85 JavaScript Interview Questions](http://career.guru99.com/top-85-javascript-interview-questions/)
* [Interview Cake JavaScript Interview Questions](https://www.interviewcake.com/javascript-interview-questions)
* [The Best Frontend JavaScript Interview Questions (written by a Frontend Engineer)](https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-\(written-by-a-Frontend-Engineer\))
* [10 JavaScript Concepts You Need to Know for Interviews](https://dev.to/arnavaggarwal/10-javascript-concepts-you-need-to-know-for-interviews)
* [Front End Interview Handbook - JavaScript Questions and Answers](https://frontendinterviewhandbook.com/javascript-questions/)
* [JavaScript Interview Questions - Quick Refresher](https://www.techbeamers.com/javascript-interview-questions-answers/)
* [The MEGA Interview Guide](https://github.com/danieldelcore/mega-interview-guide)
* [Javascript Interview Questions and Answers (2020)](https://www.interviewbit.com/javascript-interview-questions/)
* [JavaScript Modern Interview Code Challenges 2021](https://github.com/sadanandpai/javascript-code-challenges)
* [70 JavaScript Interview Questions](https://dev.to/macmacky/70-javascript-interview-questions-5gfi)

#### jQuery

* [Top 50 jquery interview questions](https://career.guru99.com/top-50-jquery-interview-questions/)
* [17 Essential jQuery Interview Questions From Toptal](https://www.toptal.com/jquery/interview-questions)
* [Top JQuery Interview Questions and Answers](https://www.techgeekbuzz.com/top-jquery-interview-questions/)

#### Front-end build tools

* [Webpack interview questions & answers](https://github.com/styopdev/webpack-interview-questions)
* [Gulp js interview questions](https://www.codeproject.com/Articles/1065184/Latest-Gulp-js-interview-questions)
* [Grunt js interview questions for beginners](http://www.talkingdotnet.com/grunt-js-interview-questions/)
* [Grunt js interview questions](https://mindmajix.com/grunt-interview-questions)

#### KnockoutJS

* [15 interview questions from CodeSample.com](http://www.code-sample.com/2014/01/knockout-js-interview-questions-and.html)
* [20 questions you might be asked about KnockoutJS in an interview for both freshers and experienced developers](http://www.codeproject.com/Articles/987899/KnockoutJS-interview-questions)

#### Less

* [Top 25 LESS Interview Questions](http://career.guru99.com/top-25-less-interview-questions/)

#### Lisp

* [10 LISP Questions & Answers](http://www.sanfoundry.com/lisp-mcqs-class/)
* [Top 18 Lisp Interview Questions from Career Guru](http://career.guru99.com/top-18-lisp-interview-questions/)

#### NodeJS

* [25 Essential Node.js Interview Questions from Adeva](https://adevait.com/nodejs/interview-questions)
* [8 Essential Nodejs Interview Questions from Toptal](http://www.toptal.com/nodejs/interview-questions)
* [Node.JS Interview Questions have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of Node.JS](http://www.tutorialspoint.com/nodejs/nodejs\_interview\_questions.htm)
* [Node.js Interview Questions and Answers](https://blog.risingstack.com/node-js-interview-questions/)
* [Top 25 Nodejs Interview Questions & Answers from Career Guru](http://career.guru99.com/top-25-interview-questions-on-node-js/)
* [Top 30 Node.Js Interview Questions With Answers](https://www.techbeamers.com/top-30-node-js-interview-questions-answers/)
* [Top Nodejs Interview Questions & Answers](https://www.interviewbit.com/node-js-interview-questions/)
* [Node.js Interview Questions in Chinese](https://github.com/haizlin/fe-interview/blob/master/category/nodejs.md)
* [Node.js Interview Questions by learning-zone](https://github.com/learning-zone/nodejs-interview-questions)

#### Objective-C

* [Interview Qs for Objective-C and Swift](http://insights.dice.com/2015/07/21/interview-qs-objective-c-swift/)
* [iOS Interview Questions For Beginners](http://ichuiphonedev.blogspot.com/2014/05/iphone-latest-interview-questions-and.html)

#### PHP

* [100 PHP interview questions and answers from CareerRide.com](http://www.careerride.com/PHP-Interview-Questions.aspx)
* [21 Essential PHP Interview Questions from Toptal](http://www.toptal.com/php/interview-questions)
* [20 Common PHP Job Interview Questions and Answers](http://www.woodstitch.com/resources/php-interview-questions.php)
* [25 Essential PHP Interview Questions from Adeva](https://adevait.com/php/interview-questions)
* [PHP interview questions and answers for freshers](http://phpinterviewquestions.co.in)
* [Top 100 PHP Interview Questions & Answers from CareerGuru](http://career.guru99.com/top-100-php-interview-questions-answers/)
* [25 PHP Interview Questions](https://www.codementor.io/php/tutorial/php-interview-questions-sample-answers)
* [26 Essential PHP Interview Questions for 2018](https://pangara.com/blog/php-interview-questions)
* [Cracking PHP Interviews Questions ebook 300+ Q\&A](https://bootsity.com/books)
* [PHP Interview Questions - Quick Refresher](https://www.techbeamers.com/latest-php-interview-questions-answers/)
* [30+ PHP Interview Questions](https://www.interviewbit.com/php-interview-questions/)

#### Python

* [26 Essential Python Interview Questions from Adeva](https://adevait.com/python/interview-questions)
* [20 Python interview questions and answers](http://www.careerride.com/python-interview-questions.aspx)
* [11 Essential Python Interview Questions from Toptal](http://www.toptal.com/python/interview-questions)
* [A listing of questions that could potentially be asked for a python job listing](https://github.com/sigmavirus24/python-interview-questions)
* [Interview Questions for both beginners and experts](http://www.bogotobogo.com/python/python\_interview\_questions.php)
* [Interview Cake Python Interview Questions](https://www.interviewcake.com/python-interview-questions)
* [Python Frequently Asked Questions (Programming)](https://docs.python.org/2/faq/programming.html)
* [Python interview questions collected by Reddit users](https://www.reddit.com/r/Python/comments/1knw7z/python\_interview\_questions)
* [Top 25 Python Interview Questions from Career Guru](http://career.guru99.com/top-25-python-interview-questions/)
* [Python Interview 10 questions from Corey Schafer](https://www.youtube.com/watch?v=DEwgZNC-KyE)
* [Python interview questions. Part I. Junior](https://luminousmen.com/post/6)
* [Python interview questions. Part II. Middle](https://luminousmen.com/post/7)
* [Python interview questions. Part III. Senior](https://luminousmen.com/post/8)
* [Python Interview Questions and Answers (2019)](https://www.interviewbit.com/python-interview-questions/)
* [100 Python Interview Questions - Quick Refresher](https://www.techbeamers.com/python-interview-questions-programmers/)
* [Top 100 Python Interview Questions from Edureka (2021)](https://www.edureka.co/blog/interview-questions/python-interview-questions/)

#### Ruby on Rails

* [20 Ruby on Rails interview questions and answers from CareerRide.com](http://www.careerride.com/ruby-on-rails-interview-questions.aspx)
* [9 Essential Ruby on Rails Interview Questions from Toptal](http://www.toptal.com/ruby-on-rails/interview-questions)
* [High-level Ruby on Rails Interview Questions](https://github.com/rishiip/ruby-on-rails-interview-questions)
* [Ruby And Ruby On Rails interview Q\&A](http://anilpunjabi.tumblr.com/post/25948339235/ruby-and-rails-interview-questions-and-answers)
* [Some of the most frequently asked Ruby on Rails questions and how to answer them confidently](https://srikantmahapatra.wordpress.com/2013/11/07/ruby-on-rails-interview-questions-and-answers/)
* [11 Ruby on Rails Interview Practice Questions](https://www.codementor.io/ruby-on-rails/tutorial/ruby-on-rails-interview-questions)
* [Top 53 Ruby on Rails Interview Questions & Answers](https://career.guru99.com/top-34-ruby-on-rail-interview-questions/)
* [10 Ruby on Rails interview questions and answers](https://www.upwork.com/i/interview-questions/ruby-on-rails/)

#### ReactJS

* [Reddit users share their expectations from ReactJS interview](https://www.reddit.com/r/reactjs/comments/3m5equ/react\_what\_interview\_questions\_to\_expect/)
* [5 Essential React.js Interview Questions](https://www.codementor.io/reactjs/tutorial/5-essential-reactjs-interview-questions)
* [React Interview Questions](https://tylermcginnis.com/react-interview-questions/)
* [Toptal's 21 Essential React.js Interview Questions](https://www.toptal.com/react/interview-questions)
* [19 Essential ReactJs Interview Questions](https://www.educba.com/reactjs-interview-questions/)
* [React Interview Questions & Answers](https://github.com/sudheerj/reactjs-interview-questions)

#### Ruby

* [21 Essential Ruby Interview Questions from Toptal](http://www.toptal.com/ruby/interview-questions)
* [15 Questions to Ask During a Ruby Interview](https://gist.github.com/ryansobol/5252653)
* [A list of questions about Ruby programming you can use to quiz yourself](https://github.com/undr/ruby-trivia)
* [The Art of Ruby Technical Interview](http://technology.customink.com/blog/2015/11/23/the-art-of-ruby-technical-interviews/)
* [Interview Cake Ruby Interview Questions](https://www.interviewcake.com/ruby-interview-questions)
* [Frequently Asked Ruby Interview Questions](https://www.javatpoint.com/ruby-interview-questions)

#### Rust

* [Top 250+ Rust Programming Language Interview Questions](https://www.wisdomjobs.com/e-university/rust-programming-language-interview-questions.html)
* [Rust Programming Interview Questions and Answers](https://www.code-sample.com/2018/02/rust-programming-interview-questions.html)
* [rust-exam: A set of questions about the Rust programming language](https://github.com/jean553/rust-exam)
* [Best Rust Programming Language Interview Questions and answers](https://www.bestinterviewquestion.com/rust-programming-language-interview-questions)

#### Sass

* [Top 17 Sass Interview Questions from Career Guru](http://career.guru99.com/top-17-sass-interview-questions/)
* [Top 10 Sass Interview Questions from educba](https://www.educba.com/sass-interview-questions/)

#### Scala

* [4 Interview Questions for Scala Developers](http://insights.dice.com/2014/09/12/4-interview-questions-scala-developers/)
* [A list of Frequently Asked Questions and their answers, sorted by category](http://www.scala-lang.org/old/faq)
* [A list of helpful Scala related questions you can use to interview potential candidates](https://github.com/Jarlakxen/Scala-Interview-Questions)
* [How Scala Developers Are Being Interviewed](http://programmers.stackexchange.com/questions/58145/how-scala-developers-are-being-interviewed)
* [Top 25 Scala Interview Questions & Answers from Toptal](http://career.guru99.com/top-25-interview-questions-on-scala/)

#### SharePoint

* [Sharepoint Interview Question For Developer](http://www.rajeshg.me/2013/05/sharepoint-developer-2010-interview.html)
* [Top SharePoint Interview Questions and Answers](https://intellipaat.com/blog/interview-question/sharepoint-interview-questions/)

#### Shell

* [Top 50 Shell Scripting Interview Questions from Career Guru](http://career.guru99.com/shell-scripting-interview-questions/)

#### Spark

* [Carefully Curated 70 Spark Questions with Additional Optimization Guides (First in the series)](https://github.com/ankurchavda/SparkLearning#spark-learning-guide)

#### Swift

* [10 Essential Swift Interview Questions from Toptal](http://www.toptal.com/swift/interview-questions)
* [Get prepared for your next iOS job interview by studying high quality LeetCode solutions in Swift 5](https://github.com/diwu/LeetCode-Solutions-in-Swift)
* [Swift Interview Questions and Answers](https://www.raywenderlich.com/762435-swift-interview-questions-and-answers)
* [Swift Programming Language Interview Questions And Answers from mycodetips.com](http://mycodetips.com/swift-ios/swift-programming-language-interview-questions-answers-987.html)
* [Your top 10 Swift questions answered](http://blog.udacity.com/2014/11/your-top-10-swift-questions-answered.html)
* [Swift interview questions and answers on Swift 5 by Raywenderlich](https://www.raywenderlich.com/762435-swift-interview-questions-and-answers)
* [Dynamic keyword in Swift](https://cocoacasts.com/what-does-the-dynamic-keyword-mean-in-swift-3)

#### Vue.js

* [List of 300 VueJS Interview Questions](https://github.com/sudheerj/vuejs-interview-questions)

#### WordPress

* [Top 45 WordPress interview questions](https://pangara.com/blog/blog45-wordpress-interview-questions-and-answers/)
* [10 Essential WordPress Interview Questions](https://www.toptal.com/wordpress/interview-questions)

#### TypeScript

* [Typescript Interview Questions](https://www.onlineinterviewquestions.com/typescript-interview-questions)
* [Top 10 TypeScript Interview Questions and Answers for Beginner Web Developers 2019](https://www.positronx.io/typescript-interview-questions-answers-2109/)

### Database technologies

#### Cassandra

* [Top 23 Cassandra Interview Questions from Career Guru](http://career.guru99.com/top-23-cassandra-interview-questions/)

#### Microsoft Access

* [Top 16 Microsoft Access Database Interview Questions from Career Guru](http://career.guru99.com/top-16-ms-access-database-interview-questions/)

#### MongoDB

* [28 MongoDB NoSQL Database Interview Questions and Answers](http://theprofessionalspoint.blogspot.com.by/2014/01/28-mongodb-nosql-database-interview.html)
* [MongoDB frequently Asked Questions by expert members with experience in MongoDB These questions and answers will help you strengthen your technical skills, prepare for the new job test and quickly revise the concepts](http://www.globalguideline.com/interview\_questions/Questions.php?sc=MongoDB)
* [MongoDB Interview Questions from JavaTPointcom](http://www.javatpoint.com/mongodb-interview-questions)
* [MongoDB Interview Questions that have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of MongoDB](http://www.tutorialspoint.com/mongodb/mongodb\_interview\_questions.htm)
* [Top 20 MongoDB interview questions from Career Guru](http://career.guru99.com/top-20-mongodb-interview-questions/)

#### MySQL

* [10 MySQL Database Interview Questions for Beginners and Intermediates](http://www.tecmint.com/10-mysql-database-interview-questions-for-beginners-and-intermediates/)
* [100 MySQL interview questions](http://www.careerride.com/MySQL-Interview-Questions.aspx)
* [15 Basic MySQL Interview Questions for Database Administrators](http://www.tecmint.com/basic-mysql-interview-questions-for-database-administrators/)
* [28 MySQL interview questions from JavaTPoint.com](http://www.javatpoint.com/mysql-interview-questions)
* [40 Basic MySQL Interview Questions with Answers](http://www.testingbrain.com/interview/mysql-interview-questions.html)
* [Top 50 MySQL Interview Questions & Answers from Career Guru](http://career.guru99.com/top-50-mysql-interview-questions-answers/)

#### Neo4j

* [Top 20 Neo4j Interview Questions from Career Guru](http://career.guru99.com/top-20-ne04j-interview-questions/)

#### Oracle

* [General Oracle Interview Questions & Answers](http://www.coolinterview.com/type.asp?iType=57)

#### Postgres

* [13 PostgreSQL Interview Q\&A](http://www.dotnetfunda.com/interviews/cat/208/postgresql)
* [Frequently Asked Basic PostgreSQL Interview Questions and Answers](http://nazafbtemplate.blogspot.com.by/2014/06/frequently-asked-basic-postgresql.html)
* [PostgreSQL Interview Preparation Guide](http://www.globalguideline.com/interview\_questions/Questions.php?sc=postgresqk\_database\_)
* [PostgreSQL Interview Q\&A from CoolInterview.com](http://www.coolinterview.com/type.asp?iType=411)

#### SQL

* [10 Frequently asked SQL Query Interview Questions](http://java67.blogspot.com.by/2013/04/10-frequently-asked-sql-query-interview-questions-answers-database.html)
* [45 Essential SQL Interview Questions from Toptal](http://www.toptal.com/sql/interview-questions)
* [Common Interview Questions and Answers](http://www.indiabix.com/technical/sql-server-common-questions/)
* [General Interview Questions and Answers](http://www.indiabix.com/technical/sql-server-general-questions/)
* [Schema, Questions & Solutions for SQL Exercising](https://github.com/XD-DENG/SQL-exercise)
* [SQL Interview Questions that have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of SQL](http://www.tutorialspoint.com/sql/sql\_interview\_questions.htm)
* [SQL Interview Questions CHEAT SHEET](https://www.interviewbit.com/sql-interview-questions/)

#### SQLite

* [Top 20 SQLITE Interview Questions from Career Guru](http://career.guru99.com/top-20-sql-lite-interview-questions/)

### Caching technologies

#### Memcached

* [Memcached Interview Questions from Javapoint](https://www.javatpoint.com/memcached-interview-questions-and-answers)
* [Memcached Interview Questions from Wisdomjobs](https://www.wisdomjobs.com/e-university/memcached-interview-questions.html)

#### Redis

* [Redis Interview Questions from Javapoint](https://www.javatpoint.com/redis-interview-questions-and-answers)
* [Redis Interview Questions from Wisdomjobs](https://www.wisdomjobs.com/e-university/redis-interview-questions-answers.html)
* [Redis Interview Questions from Career Guru](https://career.guru99.com/top-10-redis-interview-questions/)

### OS

#### Linux

* [10 Job Interview Questions for Linux System Administrators from Linux.com](https://www.linuxfoundation.org/blog/2015/07/10-job-interview-questions-for-linux-system-administrators/)
* [10 Useful Random Linux Interview Questions and Answers](http://www.tecmint.com/useful-random-linux-interview-questions-and-answers/)
* [11 Basic Linux Interview Questions and Answers](http://www.tecmint.com/basic-linux-interview-questions-and-answers/)
* [11 Essential Linux Interview Questions from Toptal](http://www.toptal.com/linux/interview-questions)
* [Top 30 Linux System Admin Interview Questions & Answers](http://www.linuxtechi.com/experience-linux-admin-interview-questions/)
* [Top 50 Linux Interview Questions from Career Guru](http://career.guru99.com/top-50-linux-interview-questions/)
* [278 Test Questions and Answers for \*nix System Administrators](https://github.com/trimstray/test-your-sysadmin-skills)
* [Linux Interview Questions - Quick Refresher](https://www.techbeamers.com/essential-linux-questions-answers/)

#### Windows

* [Top 10 Interview Questions for Windows Administrators](http://www.brentozar.com/archive/2009/07/top-10-interview-questions-for-windows-sysadmins/)
* [Top 22 Windows Server Interview Questions from Career Guru](http://career.guru99.com/top-22-windows-server-interview-questions/)
* [Windows Admin Interview Questions & Answers](http://www.01world.in/p/windows.html)

### DevOps

* [Linux System Administrator/DevOps Interview Questions](https://github.com/chassing/linux-sysadmin-interview-questions)
* [Top DevOps Interview Questions You Must Prepare In 2021](https://www.edureka.co/blog/interview-questions/top-devops-interview-questions-2016/)
* [Top 60+ DevOps Interview Questions & Answers in 2021](https://intellipaat.com/interview-question/devops-interview-questions/)
* [DevOps Interview Questions & Answers](https://www.interviewbit.com/devops-interview-questions/)

### Algorithms

* [Comprehensive list of interview questions of top tech companies](https://github.com/rishabh115/Interview-Questions)
* [A great list of Java interview questions](http://java2novice.com/java-interview-programs/)
* [Algorithms playground for common interview questions written in Ruby](https://github.com/sagivo/algorithms)
* [EKAlgorithms contains some well known CS algorithms & data structures](https://github.com/EvgenyKarkan/EKAlgorithms)
* [Top 10 Algorithms for Coding Interview](http://www.programcreek.com/2012/11/top-10-algorithms-for-coding-interview/)
* [Top 15 Data Structures and Algorithm Interview Questions for Java programmer](http://javarevisited.blogspot.com.by/2013/03/top-15-data-structures-algorithm-interview-questions-answers-java-programming.html)
* [Tech Interview Handbook Best Practice Questions](https://techinterviewhandbook.org/best-practice-questions/)
* [Daily Coding Interview Practice](https://www.techseries.dev/daily)

### Blockchain

* [Top 55 Blockchain Interview Questions You Must Prepare In 2018](https://www.edureka.co/blog/interview-questions/blockchain-interview-questions/)
* [Blockchain Interview Questions](https://mindmajix.com/blockchain-interview-questions)
* [Top Blockchain Interview Questions](https://intellipaat.com/interview-question/blockchain-interview-questions/)
* [Blockchain Developer Interview Questions and Answers](https://applicature.com/blog/blockchain-interview-questions)
* [10 Essential Blockchain Interview Questions](https://www.toptal.com/blockchain/interview-questions)
* [Top 30 Blockchain Interview Questions – For Freshers to Experienced](https://data-flair.training/blogs/blockchain-interview-questions/)
* [Most Frequently Asked Blockchain Interview Questions](https://www.digitalvidya.com/blog/blockchain-interview-questions/)

### Coding exercises

* [Common interview questions and puzzles solved in several languages](https://github.com/mre/the-coding-interview)
* [Interactive, test-driven Python coding challenges (algorithms and data structures) typically found in coding interviews or coding competitions](https://github.com/donnemartin/interactive-coding-challenges)
* [Interview questions solved in python](https://github.com/roseperrone/interview-questions)
* [7 Swift Coding Challenges to Practice Your Skills](https://www.makeuseof.com/tag/swift-coding-challenges/)

### Comprehensive lists

* [A list of helpful front-end related questions you can use to interview potential candidates, test yourself or completely ignore](https://github.com/h5bp/Front-end-Developer-Interview-Questions)
* [Front End Developer Interview Questions](http://www.aperfectmix.com/free\_web\_design/front-end-interview-questions.html)
* [Front End Interview Handbook](https://frontendinterviewhandbook.com)
* [Some simple questions to interview potential backend candidates](https://github.com/starandtina/backend-interview-questions)

### Design Patterns

* [Design Pattern Interview Questions that have been designed specially to get you acquainted with the nature of questions you may encounter during your interview for the subject of Design Pattern](http://www.tutorialspoint.com/design\_pattern/design\_pattern\_interview\_questions.htm)
* [Design Patterns for Humans™ - An ultra-simplified explanation](https://github.com/kamranahmedse/design-patterns-for-humans)
* [Design Patterns implemented in Java](https://github.com/iluwatar/java-design-patterns)
* [Design Patterns implemented in DotNet](https://www.dofactory.com/net/design-patterns)

### Data structures

* [Top 15 Data Structures and Algorithm Interview Questions for Java programmer](http://javarevisited.blogspot.com.by/2013/03/top-15-data-structures-algorithm-interview-questions-answers-java-programming.html)
* [Top 50 Data Structure Interview Questions from Career Guru](http://career.guru99.com/top-50-data-structure-interview-questions/)
* [What is Data Structure? | Top 40 Data Structure Interview Questions](https://www.interviewbit.com/data-structure-interview-questions/)

### Networks

* [Top 100 Networking Interview Questions & Answers from Career Guru](http://career.guru99.com/top-100-networking-interview-questions-answers/)
* [Networking Interview Questions](https://www.interviewbit.com/networking-interview-questions/)

### Security

* [101 IT Security Interview Questions](http://careers.simplicable.com/careers/new/101-IT-security-interview-questions)
* [How to prepare for an information security job interview?](http://searchsecurity.techtarget.com/tip/How-to-prepare-for-an-information-security-job-interview)
* [Information Security Interview Questions from Daniel Miessler](https://danielmiessler.com/study/infosec\_interview\_questions/)
* [Top 50 Information Security Interview Questions for freshers and experts](http://resources.infosecinstitute.com/top-50-information-security-interview-questions/)

### Data Science

* [Data Science Interview Questions for Top Tech Companies](https://www.dezyre.com/article/-data-science-interview-questions-for-top-tech-companies/189)
* [66 Job Interview Questions for Data Scientists](http://www.datasciencecentral.com/profiles/blogs/66-job-interview-questions-for-data-scientists)
* [Top 45 Data Science Interview Questions You Must Prepare In 2021](https://www.edureka.co/blog/interview-questions/data-science-interview-questions/)
* [Top 30 data science interview questions](https://towardsdatascience.com/top-30-data-science-interview-questions-7dd9a96d3f5c)
* [Top 100 Data science interview questions](https://www.datacamp.com/community/news/top-100-data-science-interview-questions-cc3lts7gj5j)
* [Data Science Interview Questions](https://hackr.io/blog/data-science-interview-questions)
* [160+ Data Science Interview Questions](https://hackernoon.com/160-data-science-interview-questions-415s3y2a)
* [Top Data Science Interview Questions](https://www.interviewbit.com/data-science-interview-questions/)

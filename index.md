---
layout: cv
title: Elvira 't Hart | SmartQA
output: 
    pdf_document: default
---

![profielfoto alt <](./images/profielfoto.jpg)

<br />

# Elvira 't Hart
QA Developer

<br />

| ***Information*** | ***Characteristics*** |***Interests*** |

| 28-06-1988        | Solution-oriented     | Programming    |
| Nieuwegein        | Creative              | Design         |


## Profile

Elvira is a creative and solution-oriented professional with strong communication skills and broad technical knowledge.
This combination makes her a great promoter: Getting other people enthousiastic and convinced about the importance of testing, while also being able to show how to and provide the pro's and con's of different test types and tools and how to devide these throughout a project.<br />


<br />
Before IT caught her attention Elvira worked as an independent fashion designer. Her work balanced on the border of art and fashion. She developed a way to execute designs with a laser cutter. The result: being mentioned in schoolbooks / magazines, a design worn by Lady Gaga and featured in an exhibition #Techstyle at the Museum of Fine Arts in Boston. 
<br /><br />

## Knowledge & Skills

| ***Languages***            | ***Tools***                  |
| Dutch                      | Storybook                    |
| English                    | Playwright                   |
|                            | Cypress                      |
| ***Industries***           | Webdriver.io                 |
| IT                         | Selenium                     |
| Fashion                    | Locust                       |
| Design                     | Grafana, K6                  |
|                            | Postman                      |
| ***Expertises***           | Jira                         |
| Integration tests          | Git                          |
| End-to-end testing         |                              |
| Performance & Load testing | ***Liberaries & reporters*** |
| CI                         | Vue.js                       |
| API testing                | React                        |
|                            | Testing Library              |
| ***Programming***          | Vite, Vitest                 |
| HTML                       | Chai, Mocha                  |
| CSS                        | Jest                         |
| JavaScript                 | Nyc, Istanbul                |
| TypeScript                 | Coveralls / Codecov          |
| Python                     |                              |
| Java                       | ***Applications & editors*** |
| Kotlin                     | Adobe CS Suite               |
| Bash                       | Affinity Photo & Designer    |
|                            | Coral Draw                   |
| ***OS & Networks***        | VSCode                       |
| MacOS                      | Figma                        |
| Windows                    |                              |
| Linux                      |                              |

<br />

## Work Experience

`aug 2024`
__Mindlinq__

### Test Coordinator

Mindlinq is a software platform to make youth heatlhcare more efficient and to get more insight for partnerships, healthcare providers and municipalities. 
A usertest was set up together with the project manager to interview healthcare providers. From the results useful feedback was derived and communicated back to the development team to make improvements.
<br /><br />

`mar 2024`
__SmartQA__

### Meetup Storybook

Organized a Meetup for test professionals and developers. Gave an introduction to integration testing with Storybook, provided a hands-on assignment with examples of testing differnt kinds of compnonents in isolation.
<br /><br />

`apr 2024`
__SmartQA__

### Workshop (test)containers

Organized a workshop about the use of (test)containers and databases in testing.<br />
Docker, postgreSQL, testcontainers.
<br /><br />

`okt 2023 - ...`
__ANWB__

### QA Developer

My main task was to analyse and update the test approach in Team 'Verkeer en Reisadvies'.<br />
A great way to start and get to know the codebase was to pick up part of the migration from JS to TS: adding typing to all tests. This included unit tests and Cypress tests, as well as adding typing to mocks and stubs. As a result bugs were fixed in production, fixed missing types or incomplete objects in the source code.<br />
After analysing all tests and coverage a new strategy was presented:<br />
- Replacing (html) snapshot tests with proper unit or integration tests (either Storybook or Testing Library).<br />
- Storybook was introduced as integration testing tool, after a succesfull POC, to test components in isolation.<br />
- Cypress tests were updated and prepared for migration to Playwright: what could be tested on a lower level was moved to either integration or unit tests. Focus was brought back to the happy flows, making running the tests more efficient, their focus more clear and ready (easier) to migrate to Playwright.<br />
- Introduced Figma - Storybook collaboration, so the components used in production can be seen directly next to their orignial designs in the Storybook UI.<br />
- Adding accesibility testing available in Storybook, preparing to get the application ready to conform to the WCAG standards.
<br />
<br />

After setting this up in my own team, I was asked to present my views on testing to the Frontend Chapter and help out other teams within the ANWB to discuss their testing strategy.<br />
<br />
Cypress, Playwright, Storybook, React, Testing Library, Vitest, Typescript, K6.
<br /><br />

`aug 2023 - sep 2023`
__Emendis__

### Test Automation Architect

Created POC for efficient test coverage insights.<br />
Management needs an overview of test coverage across projects. Solution needs to work for all repositories – different languages and test runners. Current script is unreliable and complex, process needs to be simplified.
<br /><br />

`jul 2022 - sep 2023`
__PwC__

### Test Automation Engineer

Supported team of PwC ‘Assisted Writing’: development of system for supporting accountants/ PwC employees with their work. Making it possible to search data from several providers, keeping up to date with critical changes regarding relevant laws, connecting law and related articles and making it possible to process this information in a document editor.
<br />

- Migrated test cases from old, non-functioning Selenium framework written in Java to Webdriver.io witting in Typescript.
- Created End to End test automation set from scratch with Webdriver.io and TypeScript.Migrated from inheritance to composition. Conscious decision as it suits test code well, easy to maintain and handover to others. Also suited the PwC application much better. 
- Specifics of chosen programming style: revealing (composed) module pattern – functional programming (instead of OOP) with revealing modules (instead of classes).
- Determined coverage
- Defined test cases and flow.
- Cucumber collaboration
- Created tests for Google, Firefox and Selenium Grid. Nightly run in Jenkins pipeline.
- Created a (python/bash) script to automatically generate the release notes by getting and combining information from GitHub and Jira.
- On request release notes needed to be made by combining numbers from GitHub and their corresponding ticket titles in Jira. Before this was done manually, after optimizing and automating this process it took seconds instead of hours.
- Created a Load test in Locust (python) to identify performance issues (and later confirmed they were fixed). Test run on development, acceptance and production environment.
PwC did not have the resources or time to hire a professional performance tester, so I took the opportunity to pick this up.<br />
Prepared a Load test for the US environment including instructions on how to set up and execute the test for the US team. Was successfully executed.<br />
Working in agile sprints. Supported team by testing ‘ready for test’ tickets for every release. Responsible for release notes, which I automated as quickly as possible. 
<br /><br />

`aug 2022`
__Valori__

### Test Automation Engineer

Workshop and Demo - Playwright<br />
After working with Playwright I was asked to give a demo about my experience with Playwright and Cypress to the senior Architects of Valori. This turned into not only a demo with code snippets and showing the possibilities of Playwright but a hands-on workshop with assignment.  
<br /><br />

`may 2022 - jul 2022`
__Keana__

### Test Automation Engineer

Supported team of Keana, development of web based TMS by creating an end-to-end automation test using Playwright. 

- Define test cases and flow 
- Determine coverage 
- BDD using testing-library 
- Accessibility testing 
- Suggest test-ability improvements to developers 
- Tool selection: proposed to use Playwright over Cypress. <br />As POC executed part of the test in both Playwright and Cypress to show the advantages in this project
<br /><br />

`2012 - 2017`
__uTest__

### Tester

Participation in crowd testing and exploratory testing. Assisted in improvement of:
BioKM app for online Lab data management, Official Rolex website, Mastercard, PowerInbox web applications, Sweet IM Toolbar
- Exploratory testing of websites 
- Executing test scenarios
- Testing of check-out systems
- Logging of found bugs
<br /><br />

`2013 - 2022`
__Elvira 't Hart__

### Fashion Designer

Avant-garde/luxury fashion design. ‘Wearable Drawings’ executed by laser cutting. Showed collections by invitation in Milan and Paris.
- Digital drawing (vector), pattern drawing, clothing construction, laser cutting.
- Coordinating production and deliveries.
- International sales of ready-to-wear items to multi-brand retailers and private customers.
- Custom designs and made-to-measure for private customers
- Participation in exhibitions, including #Techstyle MFA Boston, Amsterdam Fashionweek, World of Wearable Art New Zealand, Dutch Design Week Eindhoven.
<br /><br />

`2013 - 2022`
__Studio 't Hart__

### Freelance

Mixed assignments including: illustrations, graphic design, CSS animations, web design and web development.
- Teaching drawing classes, Melachton Schiebroek
- Illustrations for companies: logo design/ corporate identity, presentation lay-outs
- CSS Keyframes animations
- Magazine/book illustrations
<br /><br />

<br />

## Education

__Bachelor of Design, Fashion__
`2008 - 2011`

### Rietveld Academie, Amsterdam

<br />

`2007 - 2008`
__Fashion and Apparel Design__

### Willem de Kooning Academie, Rotterdam

<br />

`2006 - 2007`
__Design__

### Koninklijke Academie voor de Schone Kunsten, Antwerpen

<br />

`2000 - 2006`
__VWO__

### Stedelijk Gymnasium Nijmegen

<br />

`2005`
__Foundation Course__

### Artez Arnhem

<br /><br />

## Courses

`aug 2022 – may 2023`
__Van Python Novice naar Pythonista__

### Icttrainingen.nl (STAP-budget)

<br />

`2022`
__Valori Academy Testing course__

Testing strategies, Java, Selenium, Api testing, Postman, CI/CD Pipelines, Gherkin, Cucumber

### Valori

<br />
<br />
<br />
<br />


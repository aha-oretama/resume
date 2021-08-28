# Resume

## Agenda

- [Profile](#profile)
- [Experience, Knowledge, Skill](#experience-knowledge-skill)
- [Education/Career History](#educationcareer-history)
- [Career](#career)
    - [Mercari.Inc.: 2018/8 => now](#mercariinc-20188--now)
    - [Recruit Lifestyle Co., Ltd.: 2015/8 => 2018/7](#recruit-lifestyle-co-ltd-20158--20187)
    - [Nihon Unisys, Ltd.: 2011/4 - 2015/7](#nihon-unisys-ltd-20114---20157)
- [Cover Letter](#cover-letter)

## Profile

|key|value|
|---|-----|
|Name|関根 康史 (Yasufumi Sekine)|
|Twitter|[@AHA_oretama](https://twitter.com/AHA_oretama)|
|Qiita|<https://qiita.com/AHA_oretama>|
|SlideShare|<https://www.slideshare.net/aha_oretama>|
|Speaker Deck|<https://speakerdeck.com/ahaoretama>|
|Blog|<http://aha-oretama.hatenablog.com/>|
|GitHub|<https://github.com/aha-oretama>|
|Others(Company blog etc.)| https://engineer.recruit-lifestyle.co.jp/techblog/2017-07-11-first-rls-meetup/ |
| | https://engineering.mercari.com/blog/entry/2018-10-25-111559/ |
| | https://engineering.mercari.com/blog/entry/2018-12-07-074346/ |
| | https://engineering.mercari.com/blog/entry/2019-02-12-080000/ |
| | https://engineering.mercari.com/blog/entry/2019-04-26-060000/ |
| | https://engineering.mercari.com/blog/entry/2019-12-23-170258/ |
| | https://codezine.jp/article/detail/11599 |



## Experience, Knowledge, Skill

- Develop web applications using Java, Groovy, Kotlin JVM languages, Spring and Spring Boot.
  - Have broad and deep knowledge of Spring framework.
- Experience in developing large-scale web applications using HTML5, CSS, Node.js, React, and TypeScript
- Experience in Android application development using Java
- Knowledge and experience with EndToEnd testing tools such as Selenium, Appium, Playwright, WebdriverIO
  - Gathering and understanding of the latest testing tool information such as Espresso, puppeteer, Magic Pod, etc.
- Introducing automated testing for accessibility and performance and load testing
- Planning a testing strategy, including automated testing
- Establish, operate, and improve CI/CD
  - Experience to compare and verify CI services such as Jenkins, CircleCI, TeamCity, TravisCI, etc.
- Experience in Software Engineer in Test (SET) 
- Experience in development with a team of English speakers
- As an IT architect, selecting architecture, implementing non-functional requirements and common components
- Building and operating DevOps environment by integrating bot, CI, Slack, and other tools
- Use AWS, GCP



## Education/Career History

| Date             | Education/Career Hisotry                                     |
| ---------------- | ------------------------------------------------------------ |
| 2005/4 - 2009/3  | Bachelor of Earth & Planetary Sciences, Tokyo Institute of Technology |
| 2009/4 - 2011/3  | Master of Earth & Planetary Sciences, Tokyo Institute of Technology |
| 2011/4 - 2015/7  | Nihon Unisys, Ltd.                                           |
| 2015/8 - 2018/7  | Recruit Lifestyle Co., Ltd.                                  |
| 2018/8 - current | Mercari.Inc.                                                 |



## Career

### Mercari.Inc.: 2018/8 => now

#### SETI (Software Engineer, Tools and Infrasctructure) team: 2020/10 => now
- Project Overview
  - Improve productivity and quality in Mercalli Web groundup project (replacing all web applications with the new web application. This project is different from the re-architecture project.) 
- Achievements / Activities
  - Considering test strategy and test automation strategy; write sample code, test code, and establish CI environment for Unit testing, Regression testing, and Playwright E2E testing.
  - CI Implementation of performance, accessibility, and SEO by using Lighthouse CI and jest-axe.
  - Building a deployment pipeline. Also, build an environment for each PullRequet to improve testability.
  - Load testing of web applications on Microservice.
  - Experience in development with all communication in English.
- Technology stack
  - Language: Node.js、Golang
  - Framework: Gatsby, React, TypeScript
  - Testing: Playwright, reg-suit, Lighthouse CI, Axe
  - Others: Kubernetes, GCP, Spinnaker, CircleCI, Cloud Build, GitHub Actions

#### SETI (Software Engineer, Tools and Infrasctructure) team: 2019/4 => 2020/9

- Project Overview
  - Improve productivity and quality in the re-architecture project of the Mercari web (switching to the new web for every path)
- Achievements / Activities
  - Building a deployment pipeline. Also, building an environment for each pull request to improve testability.
  - Considering test automation strategy. Investigate and implemente the best quality assurance for the re-architecture project, which switches to the new web at every path.
  - Developing sample code, test code and CI environment for Unit testing, Visual Regression testing with Applitools and E2E testing with WebdriverIO.
  - Experience in development with English communication.
- Technology stack
  - Language: Node.js
  - Framework: React, TypeScript, GraphQL
  - Testing: WebdriverIO, Applitools
  - Others: Kubernetes, GCP, Spinnaker, CircleCI, Cloud Build

#### Automation ＆ QA team: 2018/8 => 2019/3

- Project Overview
  - Quality improvement through automated testing of Mercari mobile app
- Achievements / Activities
  - Implementation of E2E testing for Android applications using Appium and training QA engineers to write E2E tests.
  - Building and improving the CI environment for the above, and speeding it up by parallel execution.
  - Building a monitoring environment for mobile app performance using HeadSpin.
  - Visualization and monitoring of various core metrics for E2E testing using our own reporter, Cloud SQL, and Looker.
- Technology stack
  - Language: Ruby
  - Framework: Appium
  - Others: Jenkins, GCP, CircleCI, HeadSpin, Cloud SQL, Looker

### Recruit Lifestyle Co., Ltd.: 2015/8 => 2018/7

#### Head of development in HOT PEPPER GOURMET: 2017/12 => 2018/7

- Project Overview
  - As a head of development in HOT PEPPER GOURMET, I was responsible for the mid-term to long-term system strategy, the system architecture, business partner strategy and recruitment, and managed IT costs.
- Achievements / Activities
  - Establishing a mid-term to long-term strategy for the system. Clarifying the technical debt in large-scale services, and establishing and prioritizing a policy to deal with it.
  - Selecting the most suitable architecture for new services and functions, or reviewing of those implementations.
  - Plannning and managing for partner workforce accoridng to business growth.

#### Software Engineer in Test(SET): 2016/12 => 2017/11

- Project Overview
  - Launch SET team, optimize CI, increase pull request feedback, and evangelize testing.
- Achievements / Activities
  - I explained the current situation based on the incident rate and bug rate, and explained how I would work as a SET and the expected effects. 
  - There was a current debt that was taking 3-4 hours to run unit tests on CI. We selected and decided a new CI candidate, set up the CI architecture and pipeline, and optimized the CI to finish within 20-30 minutes.
  - In order to improve feedback, I introduced Lint, SonarQube, CodeCov, etc. and I changed that the feedbacks including these tools and unit test results and coverage are shown in each pull request.
  - I joined the Android team, which had no unit testing. I did update old documentation, CI, and establish unit testing methods, evangelized testing to team members.
- Technology stack
  - Language: Android Java, Java, Groovy
  - DB: Oracle
  - Middleware: Jenkins, TeamCity, (CircleCI, TravisCI), Docker, AWS
  - Tool: SonarQube, ESLint, Lint-Review, CodeCov, Danger, VersionEye

#### Skills for HOT PEPPER GOURMET on Amazhon Echo: 2017/4 => 2017/10

- Project Overview
  - Developing skills for HOT PEPPER GOURMET on Amazhon Echo
- Achievements / Activities
    - Building skills infrastructure and development environment
        - Building the initial architecture of skills
        - We created a skill with English version, then changed to support Japanese version.
- Technology stack
  - Language: Node.js
  - DB: DynamoDB
  - Framework: Alexa Skills Kit SDK for Node.js
  - Middleware: AWS Lambda

#### BookingTable: 2015/8 => 2017/3

- Project Overview
  - Development of a new "BookingTable" as a sub-site of HOT PEPPER GOURMET.
- Achievements / Activities
  - Design architecture and development including non-functional requirements.
  - Create Restfull API on the server side using Spring Boot.
  - For front end, develop SSR+SPA Universal Javascript using React, Redux, HTML5, CSS3, ES2015+.
- Technology stack
  - Language: Java, Node.js
  - Framework: Spring Boot, React, Redux
  - DB: Oracle
  - Middleware: Nginx, Tomcat, Docker, TeamCity, Jenkins

### Nihon Unisys, Ltd.： 2011/4 - 2015/7

- Project Overview
  - Requirements definition, design, development, and operation of multiple business systems. Electric power company,  pharmaceuticals & medical devices, industrial accidents
- Achievements / Activities
  - As a system integrator, I experienced full phase from the requirements definition stage to migration and operation stage.
  - In some projects, I implemented common components and non-functional requirements as a system architect.
- Technology stack
  - OS: Linux, Windows
  - Language: Java, VB.NET, JavaScript, Bash etc
  - Framework: Spring, Struts, .NET Framework, jQuery
  - DB: Oracle, SQLServer, Sybase
  - Middleware: JBOSS, IIS, Silverlight, WebSphere


## Cover Letter

I have always been interested in improving quality and development productivity, so I started working as a SET (Software Engineer in Test) by myself.
Joining a company that has a SET organization has increased my skills and mindset towards quality and development productivity even more.

I believe that development is the key to testing and  the role of SET requires a wide range of skills and knowledge, so I always try to keep up with the latest technology trends and participate in study sessions.
In addition, I am constantly improving my skills as a software engineer by copying and studying books on my own, and doing my own development.

Through my experience as a head of development, I have also gained a perspective on how I can make an impact on business.
As a SET, I am far from the business, but I am always conscious of what is most necessary for the current project and what can have a business impact.
# 2024 IDP - Roderick Bishop


## Goals & expectations

In the context of my entire career, I seek to become an interdisciplinary engineer with the ability to write code, deploy systems, and develop or integrate hardware with general aptitude across these domains. This aspiration led me to this team as a choice, as it is one of the few teams at Target that gives exposure to all of these areas.

![IDP](https://github.com/roderick-bishop11/roderick-bishop11/blob/main/IndividualDevelopmentPlans/professional/figures/Career_Goals.png)


## Looking Back to 2023

2023 was my first full-time year as an SWE. Very enlightening. I truly learned a lot and in the way of the Dunning–Kruger effect, I've learned that there is so much still to master! An exciting journey lies ahead.

From 2023's IDP:
>While on the IOT team, specifically on the Shared Services pod I am focused on learning and gaining proficiency in the areas of Backend programming, Databases & data science, devOps, security, & wireless communication. In my short time on this team I have been able to choose work that gives exposure and experience in these areas. Along with these hard skills, I aspire to continue to network & develop soft skills necessary to excel at leadership roles.
>

Of those goals, I've completed work in the following areas, represented as completion to personal satisfaction.

- **Backend Programming:**  ![backend_progress](https://geps.dev/progress/60)
  - Took responsibility for 2 applications, 1 deprecated & the other still in development
  - Learned more about what's going on under the hood with Gradle as a build tool as well as Kotlin as a language. Topics like project & task configuration, dependency management,  
  - Error Flow conventions
  - Observability and metics
  - Testing
  - Deployment
  - Using CLI's & other tools

- **Security:**  ![security_progress](https://geps.dev/progress/15)
  - Completed work relating to request authentication; tokens, goProxy, enterprise secret practices etc.
  - Completed some work around remediating security vulnerabilites and the tooling to help with that.

- **Data Science:**  ![data_science_progress](https://geps.dev/progress/0)
- No progress on this stated goal.

Over the course of the year however, I have been able to deliver work for the team that required learning in a few areas with great satisfaction. The following I consider my **Experiential Learning Wins**:

- Unit Testing: ![unit_testing_progress](https://geps.dev/progress/75)
  - Using Kotlin's Kotest & Micronaut as tools, I learned to test kotlin native applications as well as open source external app libraries. General exposure to testing units across API components was garnered as well. Testing controllers by using a test client that makes the request to the controller, validating payloads, responses and service calls were great experiences. I learned about testing services as well as testing extensions/components that aren't classes for functionality.
  - Mocks, Stubs, & Spy's using Mockk & Mockito to isolate units and behaviors we want to test.

- Data-Driven Testing (DDT): ![data_driven_testing_progress](https://geps.dev/progress/80)
  - data driven tests
  - dynamic mocking for DDT involving tables and index vars
  - test scopes & test runtimes

- Application Design ![app_progress](https://geps.dev/progress/40)
  - With both Lockjaw (Agent-proxy) and Benatar (Camunda Cockpit server app) I got to do app design work. I definitely understand now how important this phase of the SDLC is. There is still so much to learn here for me in this area but the experience that I did gain will help streamline the process of design as well as development in the future.

## What I'm working on now in 2024

This year, I'd like to carry over my learning intent in security, backend programming in terms of writing code or deploying systems with scalability in mind. Inspired by last year's bonus experiential learning I have intents to focus story work and learning around:

- Application Security
- Deployment & DevOps
- Horizontal Scaling of systems and apps
- Databases & Data Access
- App Integration and Testing
- *Networks - learning Topic*
- *App Compile & Runtime - learning topic*

As an individual contributor, I'd like to simply write as much code as possible. Last year was integral to developing the capacity & capability necessary to deliver more for the team. I plan to continue to scale over last year's deliverabiles, kicking off the year with the implementation of Lockjaw which was started last year. With the recent work on realigning our team to OKR's as well, it's easier for me to see where I can help the team after this initial accomplishment. I have observed substantial changes in speed & correctness of code delivery from my end especially with respect to testing, a refinement of approach and process with new applications, and greater knowledge of or influence over RFID applications as the year progressed.


## Evaluation against 2024's goals as of 11/29/24, expressed as percentile of personal/team satisfaction with coverage of content

| Goal | Percent | Notes |
| ---- | :------: |  ---- |
|Project Delivery | ![app_progress](https://geps.dev/progress/60) | Lockjaw Delivery is no longer an objective- learning that sometimes projects don't deliver the value that's intended or cost more than the value they bring. Pivoted to smaller projects & freature work for existing or newer components. I've also had the opportunity to build & deliver a tool; the config-scraper for other engineers to use. Learnings around code reviews, personal project delivery workflows, collaborating w/other developers to develop via roadmap, prototyping & solution analysis were all done experientially. To date, I've delivered more code with smoother review processes this year than last; even while missing a month due to FMLA. |
| Application Security| ![app_progress](https://geps.dev/progress/45) | Per the Dunning-Kruger effect, my first foray into app security is revealing how much more there is to learn. This year involved hands on hacking using [OWASPs Juice Shop](https://owasp.org/www-project-juice-shop/) as well as threat modeling for my team. Also, operational readiness reviews were conducted w/Lockjaw as well as other production components. Lots left to learn as far as general knowledge, but learning App Security w/ Target as a teach org was the prime directive. There might be more this year. |
| Deployment & DevOps | ![app_progress](https://geps.dev/progress/55) | Some elements of Deployment & DevOps has been incorprated in sprint work such as database OS upgrades, app security vulnerability updates, and deployment of artifacts and apps to various environments. New role as Security Ninja aids in gaining more experience in this realm. |
| Horizontal Scaling of systems and apps | ![app_progress](https://geps.dev/progress/25)| Some learning around system design/architecture where scale is built in, operational readiness, prep for scale, & load testing applications to measure throughput and inefficiencies. All of these subjects were covered this year. Load testing with gatling using Scala, op readiness for Lockjaw, scaling of Drax near end of the year, also profiling JVM apps & heap analysis to troubleshoot Yondu(camunda engine). |
| App Integration & Testing | ![app_progress](https://geps.dev/progress/40)| Lots of opportunities for this area, but also lots of work. I've learned so much and completed more unit tests, integration tests, stress tests, load tests, etc. this year than ever before.|
| Databases & Data Access | ![app_progress](https://geps.dev/progress/20)| Completed work relating to migrating DBs, along with on-call rotations requiring real-world use of postgres DML. Took time to learn about transactions, locks, metrics & telemetry, internet connections, meterialized views, top-N-analysis, roles, data rollups, and permissions in postgres this year. This builds upon my knowledge of DDL/DML from college while also adding some DBA skills as well. Lots more to learn around queries, aggregation, db management, and performance. |
| *Networks - learning Topic* |![app_progress](https://geps.dev/progress/10) | Gave Networking 101 presentation to EEPs this winter. Delving deeper into the subject by administering a homelab! |
| *App Compile & Runtime - learning topic* |![app_progress](https://geps.dev/progress/35) | Valuable spike time was spent learning more about JVM Heaps & heap analysis using `jmap`, G1GC, memory allocation optimization & analysis. Also spent learning time on topics like Gradle, Java's JIT compiler, the JVM itself, differences between JVM successors like Kotlin & Scala. Also took time to learn about the GCC compiler, compile implementations in RUST also. |

## Notes on delivery & professional aspirations

## Notable non-engineering Work/opportunities this calendar year

- Genesys Works mentor- (Winter 2024)
- Attended Afrotech 2024: participating in volunteer work, Joyhacks event with Target & Shipt as well as networking & the conference. (November 2024)
- Showed dedication to Target’s core values by volunteering at various Target Events
  - Morehouse College Target Tech Day & Hackathon (March 2024)
- TLP Peer Mentor program (summer 2024)
  - Carrying over mentorship of one mentee from the 2023 peer mentor program.(Intern is returning)
  - Took on 2 new interns this year, with one returning. All 3 received full-time offers.
- Presented Networking 101 presentation to EEPs (January, 2024)

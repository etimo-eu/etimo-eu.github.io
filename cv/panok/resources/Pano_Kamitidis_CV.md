---

# Pano Kamitidis

**Java Architect, Developer & Consultant — Freelance**

*Open to: freelance only — Java architecture / senior backend engagements. Hybrid in Belgium or fully remote within EU. No on-site, no employment contracts.*

## Contact

- **Residence:** Helchteren, Belgium
- **Email:** <pano.k@etimo.eu>
- **Website (CV):** <https://etimo.eu/cv/panok/>
- **Phone:** +32 487 61 78 60

## Professional Summary

Experienced Java backend specialist with **11+ years of professional experience** designing, building and maintaining enterprise applications across eHealth, banking & insurance, and telecom. Currently Application Architect at Smals (Belgian federal eGov ICT partner) since 2020, having progressed from Java developer in the same team. Comfortable switching between hands-on coding and architecture work, leading migrations and modernizations (monolith → microservices, on-prem → OpenShift), and mentoring developers.

Multidisciplinary background — laboratory science before software — informs a systems-thinking, quality-first approach. Team player who works equally well pro-actively and independently. Eager to learn and deliver quality work efficiently.

## Core Competencies

- Application & software architecture
- Microservices design, migration and modernization
- Cloud-native application development
- Container orchestration on OpenShift (Kubernetes-based platform)
- RESTful API design (incl. healthcare standards: FHIR / HAPI FHIR, KMEHR)
- Authentication & authorization (OIDC, OAuth2)
- Performance tracing & observability (Zipkin, Elasticsearch)
- Code review & technical mentoring
- Technical leadership (incl. substitute Scrum Master)
- Agile / Scrum delivery

## Technical Skills

- **Programming languages:** Java (11+ yrs), SQL (11+ yrs), PL/SQL, JavaScript, HTML, CSS
- **Frameworks & libraries:** Spring (10+ yrs, incl. Boot, Cloud, Data, Web, Batch), Hibernate / JPA (10+ yrs), Lombok, AssertJ, Mockito, JUnit, TestNG, QUnit, Quartz, Apache CXF, JSF, JSP, Angular
- **APIs & protocols:** REST (10+ yrs), SOAP, OIDC, OAuth2, FHIR (HAPI FHIR), KMEHR, WebSocket
- **Cloud-native & containers:** OpenShift (Kubernetes-based), Docker, Docker Compose, container orchestration
- **Application servers:** Tomcat, Jetty, JBoss EAP, WebLogic
- **Databases:** PostgreSQL, Oracle, MySQL, H2, HSQLDB, Redis
- **Observability & quality:** Zipkin, Elasticsearch, Sonar
- **Build & CI/CD:** Maven, Gradle, Jenkins, Flyway
- **Version control & collaboration:** Git, GitLab, Bitbucket, Subversion, Jira, Confluence
- **Tools:** IntelliJ IDEA, Eclipse, SoapUI, HighCharts
- **Mobile:** Android
- **Methodologies:** Agile, Scrum, OOP, ORM, MVC, microservices, REST
- **Operating systems:** Linux, Windows
- **Domains:** eHealth (Vitalink, FHIR, KMEHR), banking & insurance (Belfius), telecom (Vodafone / Hollandsnieuwe), document management, eID authentication

## Professional Experience

### Application Architect & Java Developer — Smals
**2020 – present** | Belgium

Smals is the ICT partner of Belgian federal social-security and eHealth institutions. Working in the Vitalink team (the development team) on the national platform that lets healthcare providers securely share patient data. Progressed from Java developer to Application Architect during tenure.

#### As Application Architect

- Design and implement software architecture in close collaboration with solution architects.
- Oversee software development and release cycles end-to-end.
- Lead investigation, preparation and migration to new technologies and infrastructure (e.g. OpenShift 3 → 4, high-availability cluster).
- Single point of contact for technical matters; align team output with customer goals.
- Hands-on Java development and code review alongside architectural responsibilities.
- Mentor and coach junior developers; conducted numerous technical interviews for new hires.
- Substitute Scrum Master / team lead when required.
- Assist in estimations, story prioritization, sprint preparation and roadmap planning.

#### As Java Developer (prior phase of the role)

- Expanded, improved and maintained Java backend services in production.
- Provided technical support and expertise to team and stakeholders.
- Investigated and analyzed incidents and production problems.
- Led and contributed to migrations to newer technologies and platforms.
- Performed peer code reviews and coached junior developers.
- Occasionally conducted technical interviews.

#### Key Project: Vitalink

Vitalink is the Belgian national system that allows healthcare providers to easily and securely share digital data about their patients. Providers integrate via their own software packages; patients can consult their own data via the MyHealthViewer.

**Vitalink FHIR** (current generation, successor of Vitalink KMEHR)

- *As developer:* participated in MVP development; afterwards continued expanding functionality while improving and maintaining the platform.
- *As architect:* delivered quality efficiently as the technical point of contact, helping lead the team toward both internal and customer goals.
- Key achievements:
  - Introduced performance tracing with Zipkin across the service fleet.
  - Led migration to a new high-availability infrastructure.
  - Led OpenShift 3 → 4 migration across multiple microservices.
  - Refactored multiple microservices and significant portions of the shared codebase.
- *Technologies:* Java 11–17, Spring Boot, Spring Cloud, Spring Web, Spring Data, OIDC, OAuth2, (HAPI) FHIR, JPA/Hibernate, Flyway, Zipkin, Elasticsearch, Mockito, AssertJ, REST, OpenShift, PostgreSQL, GitLab, Git, Maven, Sonar, Angular, Docker, Lombok, Confluence, Jira, Tomcat, Jenkins, IntelliJ IDEA.

**Vitalink KMEHR** (predecessor of Vitalink FHIR)

- Expanded, improved and maintained the legacy KMEHR-based platform.
- access-manager: control who has what kind of access to what data, based on blacklist tables.
- Migrations: JBoss EAP 6 → 7, Spring → Spring Boot, monolith → multiple microservices, Java 8 → 11.
- Extended REST services to support POST, PUT and DELETE operations.
- Added and updated business logic; bug fixing and change requests.
- *Technologies:* Java 8–11, Docker, Docker Compose, Spring Boot, Spring Data, Spring Batch, OIDC, OAuth2, JPA/Hibernate, Mockito, AssertJ, REST, SOAP, JBoss EAP, OpenShift, PostgreSQL, H2, HSQLDB, GitLab, Git, Maven, Lombok, Apache CXF, Confluence, Jira, Sonar, SoapUI, JSF, IntelliJ IDEA, Jenkins.

---

### Application Engineer (Java) — Belfius Insurance
**2016 – 2020** | Belgium

Belfius is one of Belgium's major bank-insurance groups. Worked on internal and customer-facing applications within the insurance branch.

- Planned, designed, built and tested new software applications end-to-end.
- Built technical design proposals and proofs of concept in close interaction with architects.
- Provided technical support and expertise across multiple applications.
- Investigated and analyzed incidents and production problems.
- Improved and extended existing software & applications.
- Acted as application owner for multiple applications — responsible for technical state, roadmap, and stakeholder communication.

#### Flagship projects

- **Sign Platform:** the main application responsible for the signing process of all documents for Belfius Insurance and Bank — e.g. document signing of insurance documents via the Belfius app.
- **WebSocket framework:** server + JavaScript client library for socket-based front-end integration across multiple applications; manages all connections and message dispatching. Platform-level work consumed by other Belfius front-ends.
- **eID integration:** background Belgian-eID card-reader application that pushes identity data to a message queue; web forms consume the queue and auto-fill themselves with the cardholder's identity data.
- **QR Login:** alternative login flow. Led the project end-to-end and built the back-end.

#### Other contributions

- **URL Generator:** REST service that builds URLs from request and query parameters, replacing hard-coded URLs across applications with centralized management.
- **Auto-start apps:** REST service managing a per-user list of Windows start-up applications, paired with a companion launcher application.
- **DIGIS:** new features and improvements to a custom-made document management system.
- **DIBIS:** new functionality on a standalone Java policy-management application.
- **Network segregation migration:** moved the applications above to a new segregated and segmented network.
- **AEM POC:** proof of concept migrating the in-house front-end framework from SDL Tridion to Adobe AEM.

*Technologies:* Java, JavaScript, Spring, Hibernate, JPA, REST, WebSocket, QUnit, Mockito, HSQLDB, Oracle, Git, Maven, Eclipse, Jira, Bitbucket.

---

### Java Developer — QNH Belgium
**2014 – 2016** | Belgium

QNH was a Belgian IT consultancy delivering Java solutions to clients across Belgium and the Netherlands. Worked across multiple client engagements as well as internal projects.

- Built new software applications and proofs of concept.
- Provided technical support and maintenance for client systems.
- Contributed to feature extensions and improvements of existing software applications.

#### Key Projects

- **Hollandsnieuwe / Vodafone (2014 – 2015):** collaborated on a multi-brand customer provisioning platform for the Vodafone network. Wrote migration software to transfer all customers to a new platform; (re)wrote use cases and software for communication with new/updated services; refactored the payment process to speed up and stabilize the batch process; ongoing maintenance.
  - *Technologies:* Java, ATG Web Commerce, WebLogic, PL/SQL, HTML, JSP, Subversion, Scrum, Mockito, TestNG, SoapUI, IntelliJ IDEA.
- **Simcard management (2015):** modified an existing simcard management web application — switched the web server to Jetty and the database to HSQLDB for local development, added Flyway for DB migrations, added Redis-backed HTTP session via Spring Boot, added user and account management (with visibility settings).
  - *Technologies:* Java, Angular, SQL, REST, Spring Boot, Git, Flyway, HSQLDB, Tomcat, IntelliJ IDEA, Quartz.
- **DCC (Diplomatic Card Company, 2014):** proof of concept of an Android app with a web-services back-end. Core logic placed in the back-end so other mobile platforms could be added later. Android app: shows nearby stores sorted by geolocation, plus their current promotions. Back-end: store and promotion management.
  - *Technologies:* Android, REST, Git, PostgreSQL, Flyway, Java.
- **Hymedis (2014):** set up the Hymedis project on Linux and documented it; automated quarterly reporting and produced a web version of the report.
  - *Technologies:* Java, HighCharts, HTML, CSS, Jira, Confluence, Bitbucket, Git, Spring, MySQL, Flyway.

*Combined technologies across QNH engagements:* Java, ATG Web Commerce, WebLogic, PL/SQL, JSP, Subversion, Scrum, Mockito, TestNG, SoapUI, Android, REST, Git, PostgreSQL, MySQL, Flyway, HighCharts, HTML, CSS, Spring, Spring Boot, Angular, SQL, HSQLDB, Tomcat, Quartz, IntelliJ IDEA.

---

### Career Transition — Java Enterprise Developer Programme (VDAB)
**2013** | Belgium

Full-time public-sector retraining programme following a career switch from laboratory science into software. Completed with an internship at QNH Belgium that led directly into permanent employment from 2014.

- Java SE, Spring, JPA, REST, OOP, design patterns, version control, Maven.
- Internship at QNH Belgium.

---

### Laboratory Technician (QC) & Wastewater Treatment Officer — ECO Belgium
**2010 – 2012** | Belgium

Pre-software career in industrial chemistry. The multidisciplinary background informs my systems-thinking approach to software problems today.

- Quality control of processed products, including adjustments to meet quality standards.
- Issued certificates of analysis on input and output samples.
- Ensured discharged wastewater values remained within environmental compliance limits.

---

### Laboratory Technician (QC, Microbiology) — Vleminckx
**2009 – 2010** | Belgium

- Quality control of processed products, including adjustments to meet quality standards.
- Microbiology.

---

### Laboratory Technician (QC) — Mathys
**2008 – 2009** | Belgium

- Quality control of processed products, including adjustments to meet quality standards.

## Education

- **Bachelor's degree, Applied Computer Science** — PXL University of Applied Sciences and Arts, Hasselt | 2018
  *Specialization: application development. Pursued part-time alongside professional employment.*
- **Associate's degree, Biotechnology** — GroepT, Leuven | 2014
  *Internship at BIOMED, Biomedisch Onderzoeksinstituut, UHasselt.*
- **Java Enterprise Developer** — VDAB | 2013
  *Public-sector vocational IT programme. Internship at QNH Belgium.*
- **Secondary education** — Sint-Jan Berchmansinstituut | 2005
  *Science-math, Economics-math, Latin.*

## Certifications

- **Oracle Certified Associate, Java SE 8 Programmer** — Oracle
- **Professional Scrum Master I (PSM I)** — Scrum.org
- **Programming in HTML5 with JavaScript and CSS3** — Microsoft

## Languages

- **Dutch** — C2 (native)
- **English** — C1 (advanced; professional working proficiency)
- **French** — B1 (intermediate)
- **Greek** — A2 (elementary)

## Additional Information

### Working style

Pre-IT scientific background drives a quality-first habit and a preference for understanding the whole system before changing parts of it. Equally comfortable as IC and tech lead.

### Laboratory background (legacy skills from prior career)

- Transforming cells, plasmid isolation, multiplex and sequence PCR, electrophoresis.
- Quality control: input/output control, certificates of analysis, adjusting processed products to meet quality standards.

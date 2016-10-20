# Quality Attributes Examples

* [Introduction](#introduction)
* [IEEE Recommended Practice](#ieee)
* [Users and developers](#users-and-developers)
* [Subjective and objective](#subjective-and-objective)
* [Big list of categories and examples](#big)


<a name="introduction"><h2>Introdcution</h2></a>

* [Non-functional requirements-- do we really care?](http://www.slideshare.net/osscube/non-functional-requirements-do-we-really-care)
* [What is a functional and non-functional requirement? - Stack Overflow](http://stackoverflow.com/questions/16475979/what-is-functional-and-non-functional-requirement)

Examples of 
Execution qualities, such as security and usability, which are observable at run time.
Evolution qualities, such as testability, maintainability, extensibility and scalability, which are embodied in the static structure of the software system.


<a name="ieee"><h2>IEEE Recommended Practice</h2></a>

Examples based on [IEEE Recommended Practice for Software Requirements Specifications](http://www.utdallas.edu/~chung/RE/IEEE830-1993.pdf)

* Performance requirements
* Interface requirements
* Operational requirements
* Resource requirements
* Verification requirements
* Acceptance requirements
* Documentation requirements
* Security requirements
* Portability requirements
* Quality requirements
* Reliability requirements
* Maintainability requirements
* Safety requirements


<a name="users-and-developers"><h2>Users and developers</h2></a>

Users and developers typically want different kinds of quality attributes.

<table>
<tr><th>Important to users</th><th>Important to developers</th></tr>
<tr><td>Usability</td><td>Maintainability</td></tr>
<tr><td>Availability</td><td>Scalability</td></tr>
<tr><td>Reliability</td><td>Testability</td></tr>
</table>


<a name="subjective-and-objective"><h2>Subjective and objective</h2></a>

Examples of subjective attributes and objective attributes:

<table>
<tr><th>Subjective</th><th>Objective</th></tr>
<tr><td>Fast</td><td>Within 1 second</td></tr>
<tr><td>Easy</td><td>A majority of focus group users check the survey box "this is easy"</td></tr>
<tr><td>Frequent</td><td>Every hour on the hour</td></tr>
<tr><td>Secure</td><td>All password storage uses scrypt encryption</td></tr>
<tr><td>Available</td><td>Our third-party monitoring service proves our uptime is 99% or higher</td></tr>

</table>


<a name="big"><h2>Big list of categories and examples</h2></a>

Accessibility:
* Can a blind person navigate the site using a screen reader?

Accountability:
* Does each image have a watermark or similar indicator of who owns it and the usage rights?

Accuracy:
* Does an estimate come within 1% of the true value?

Adaptability:
* TODO

Administrability:
* TODO

Affordability:
* Is our product priced within 10% of our competitor's similar product?

Agility:
* How long does it take to go from a new idea to deploying the idea as a new feature?

Auditability:
* How is information managed to ensure accuracy, warrantability, traceability, etc.?
* What are the policies for company retention, legal discovery, regulatory compliance, etc.?

Autonomy:
* TODO

Automatability:
* Are we able to interaction with the system by using command line interfaces, scripts, etc.?

Atomicity:
* How do we verify that a transaction is "all or nothing", rather than stuck at partially-completed?

Availability:
* We are aiming for 99.99% uptime according to our monitoring service.
* What are expectations for uptime, hours of operation, maintenance windows, outage mean time to recovery, etc.?
* Where are the most important locations of operation, and are there any special connection requirements?

Capacity:
* How many transactions does the system need to be able during normal usage and also at peak usage?
* What resources are expected, in terms of memory, storage, processing, bandwidth, etc.?
* What happens if the system ever exhausts a resource?

Compatibility:
* Our API data conforms to the JSON specification.

Composability:
* TODO

Configurability:
* TODO

Controllability: 
* Can we control the state of the system by using administration tools?

Consistency:
* To what degree are the system and its data consistent, such as changing only in allowed ways?

Correctness:
* TODO

Credibility:
* TODO

Customizability:
* TODO

Debugability:
* TODO

Degradability:
* TODO

Determinability:
* TODO

Demonstrability:
* TODO

Dependability:
* TODO

Deployability:
* TODO

Discoverability:
* TODO

Distributability:
* TODO

Durability:
* When a transaction is committed, is it preserved, even in the event of power loss, crashes, or errors?

Effectiveness:
* TODO

Efficiency:
* TODO

Evolvability:
* TODO

Extensibility:
* TODO

Failure transparency:
* TODO

Fault-tolerance:
* How will the system handle failures?
* What are the goals for fault trapping?

Fidelity:
* TODO

Flexibility:
* TODO

Heterogeneity:
* To what extent do we use diverse technologies, such as multiple programming languages and frameworks?

Homogeneity: 
* To what extent do we use the same technologies, such as one programming language and framework?

Inspectability:
* TODO

Installability:
* TODO

Integrity:
* What are goals for consistency of events, values, methods, measures, expectations, and outcomes?
* Are there needs for application integrity, such as checksumming binaries, or signing transactions, etc.?
* Are there needs for data integrity, such as referential integrity, or randomness guarantees, etc.?

Interchangeability:
* TODO

Interoperability:
* TODO

Instrumentability:
* To what degree is it possible to instrument the system?

Isolateability:
* To what degree are items are kept separate, such as for ACID transactions or testing?

Learnability:
* TODO

Maintainability:
* How easily can the system be maintained?
* What are the goals for conformance to best practices, coding standards, enterprise architecture patterns, etc.?
* What documentation is needed for the system, training, versioning, etc.?

Manageability:
* TODO

Mobility:
* TODO

Modifiability:
* TODO

Modularity:
* TODO

Monitorability:
* the degree to which it is possible to monitor the system.

Observability:
* the degree to which it is possible to observe the system.

Operability:
* TODO

Orthogonality:
* TODO

Portability:
* TODO

Precision:
* TODO

Predictability:
* TODO

Process capabilities:
* TODO

Producibility:
* TODO

Provability:
* TODO

Recoverability:
* What is the disaster recovery plan?
* What is the data policy for backups, retentions, proof of fitness for recoverability, fire drills, etc.?
* Are there any sensitive data that involves special handling because of privacy, or legality, or other reasons?
* What are the Recovery Point Objectives (RPO) and Recovery Time Objectives (RTO)?

Relevance:
* TODO

Reliability:
* Mean Time Between Failures (MTBF): what are the acceptable thresholds for outages, down time, material errors, etc.?
* Mean Time To Recovery (MTTR): if something breaks, how much time is expected to get everything corrected and running?

Repeatability:
* TODO

Reproducibility:
* TODO

Resilience:
* TODO

Responsiveness:
* How fast are response times for browser page loading, API responses, software downloads, etc.?
* What is the process for tracking query times, reporting times, ETL times, etc.?
* Throughput

Reusability:
* TODO

Robustness:
* How will the system handle failures?
* What are the goals for fault trapping, application hooks, SMNP, etc.?

Safety:
* TODO

Scalability:
* TODO

Seamlessness:
* TODO

Self-sustainability:
* TODO

Serviceability:
* TODO

Securability:
* How are authentication credentials encrypted and managed?
* How are authorization access control rules managed?
* Do passwords have any requirements, such as length, special characters, expiry, recycling policies, multi-factor authentication (MFA)
* What are the encryption requirements for data in flight and/or data at rest?
* What is the policy if someone reports a possible data breach?

Separability:
* The extent to which each item has a single well defined responsibility.

Simplicity:
* TODO

Stability:
* TODO

Standards compliance:
* What standards are involved, such as ISO, IEEE, Internet RFCs, etc.? 
* What are the goals for conformance to Enterprise Architecture standards, technical design standards, coding standards, etc.?
* What automatic standards validators are available, such as code quality metric tools, source code linters, etc.?

Supportability:
* TODO

Survivability:
* TODO

Sustainability:
* TODO

Tailorability:
* TODO

Testability:
* TODO

Timeliness:
* TODO

Traceability:
* TODO

Transparency:
* TODO

Ubiquity:
* TODO

Understandability: 
* the system items are self-explaining, or documented, or diagrammed, etc.

Upgradability:
* TODO

Usability:
* Are there goals or standards for user interfaces, look and feel, keyboard navigation, image alt tags, etc.?
* What are the needs for internationalization, localization, languages, spellings, regional keyboards, etc.?
* What help is available for the users?

Warrantability:
* for guarantees or promises, express or implied, such as for legal contracts, SLAs, and QoS.

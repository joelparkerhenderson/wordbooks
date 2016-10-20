# Quality Attributes Examples

Subjective attributes versus objective attributes:

<table>
<tr><th>Subjective</th><th>Objective</th></tr>
<tr><td>Fast<br>Immediate<br>Real Time</td><td>Within 1 second</td></tr>
<tr><td>Easy<br>Simple<br>Friendly</td><td>A majority of focus group users check the survey box "this is easy"</td></tr>
<tr><td>Safe<br>Secure<br>Protected</td><td>All passwords storage uses scrypt encryption</td></tr>
<tr><td>Dependable<br>Reliable<br>Always Up</td><td>Our third-party monitoring service proves our uptime is 99% or higher</td></tr>
<tr><td>Frequently<br>Regularly<br>Often</td><td>Every hour, on the hour</td></tr>
<tr><td>State-of-the-art<br>Best-practice<br>Highly-rated</td><td>The product is in the Gartner magic quadrant within the past 30 days</td></tr>
</table>

Capacity:
* How many transactions does the system need to be able during normal usage and also at peak usage?
* What resources are expected, in terms of memory, storage, processing, bandwidth, etc.?
* What happens if the system ever exhausts a resource?

Security:
* How are authentication credentials encrypted and managed?
* How are authorization access control rules managed?
* Do passwords have any requirements, such as length, special characters, expiry, recycling policies, multi-factor authentication (MFA)
* What are the encryption requirements for data in flight and/or data at rest?
* What is the policy if someone reports a possible data breach?
 
Recoverability:
* What is the disaster recovery plan?
* What is the data policy for backups, retentions, proof of fitness for recoverability, fire drills, etc.?
* Are there any sensitive data that involves special handling because of privacy, or legality, or other reasons?
* What are the Recovery Point Objectives (RPO) and Recovery Time Objectives (RTO)?

Auditability:  
* How is information managed to ensure accuracy, warrantability, traceability, etc.?
* What are the policies for company retention, legal discovery, regulatory compliance, etc.?

Performance:
* How fast are response times for browser page loading, API responses, software downloads, etc.?
* What is the process for tracking query times, reporting times, ETL times, etc.?

Availability:
* What are expectations for uptime, hours of operation, maintenance windows, outage mean time to recovery, etc.?
* Where are the most important locations of operation, and are there any special connection requirements?

Reliability:
* Mean Time Between Failures (MTBF): what are the acceptable thresholds for outages, down time, material errors, etc.?
* Mean Time To Recovery (MTTR): if something breaks, how much time is expected to get everything corrected and running?

Robustness:
* How will the system handle failures?
* What are the goals for fault trapping, application hooks, SMNP, etc.?

Integrity:
* What are goals for consistency of events, values, methods, measures, expectations, and outcomes?
* Are there needs for application integrity, such as checksumming binaries, or signing transactions, etc.?
* Are there needs for data integrity, such as referential integrity, or randomness guarantees, etc.?

Maintainability:
* How easily can the system be maintained?
* Conformance to Enterprise Architecture standards
* Conformance to Technical design standards
* Conformance to coding standards
* What are the goals for conformance to best practices, coding standards, enterprise architecture patterns, etc.?

Usability:
* Are there goals or standards for user interfaces, look and feel, keyboard navigation, image alt tags, etc.?
* What are the needs for internationalization, localization, languages, spellings, regional keyboards, etc.?

Documentation:
* User Documentation
* System Documentation
* Help
* Training Material
* Semantic ersioning

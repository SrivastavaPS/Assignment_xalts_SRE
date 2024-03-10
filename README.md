# Assignment_xalts_SRE

**Problem**
As a Site Reliability Engineer (SRE), you are responsible for ensuring the reliability and availability of our systems. In this assignment, you will participate in an incident response simulation focused on a hypothetical scenario involving a service outage.

**Incident Description 1 :**

Service Affected: Payment Gateway

Symptoms:
      ● Sudden spike in error rates exceeding the threshold.
      ● Complete loss of connectivity to the payment gateway.
      
Impact:
      ● Inability to process customer transactions.
      ● Revenue loss during peak hours.

Timeline:
      ● Incident Start Time: 14:30 UTC
      ● Peak Error Rates Observed: 14:45 UTC
      ● Service Outage Detected: 15:00 UTC

Environment Details:

System Architecture:
      ● Payment Gateway Service: Hosted on Kubernetes clusters
      ● Backend Database: Amazon RDS (MySQL).
      ● Frontend Application: Deployed on AWS amplify.

Monitoring Tools:
      ● New Relic for application performance monitoring.
      ● CloudWatch for AWS resource monitoring.
      ● Splunk for log analysis

Provide steps of response by detailing out the response plan, parameters to be observed, probable root causes and proposed solutions for the same.

**Incident Description 2:**
A user accidentally deletes a key file containing critical credentials stored on a server, there is an immediate need to recover the deleted file to prevent service disruption and potential security breaches. Provide a robust recovery process to restore the deleted access key file promptly while minimizing the impact on system availability and security.Also propose a plan to avoid such incidents in future.

**Assignment Deliverables:**

_1. Scenario 1:_ Provide an incident response Plan for the first incident scenario detailing the incident response plan, parameters to be observed, probable root causes and proposed solutions for the same.

_2. Scenario 2:_ Provide a robust recovery process to restore the deleted access key file promptly while minimizing the impact on system availability and security. Also propose a plan to avoid such incidents in future.

_3. Create a github repo_ with all the code, documents, readme and other resources included in your submission and share the repo with atulxalts and jaywardhan01

_4. Share a link_ to your github repo via email 
    a. atul.mishra@xalts.io
    b. jaywardhan.sawale@xalts.io

# CS-305-Software-Security

- Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their clients. The organization has a RESTful web application programming interface (API) and needs protection from external threats. My role was to identify any security vulnerabilities within their existing software.

- I tested the code base to identify any security vulnerabilities using the CVE and NVD databases. It's critical to implement secure coding best practices because it helps remove commonly exploited software vulnerabilities, which keeps business and their users safe from attacks. The value that software security adds to a company's overall wellbeing is user trust.

- I found it helpful to use the CVE and NVD databases because they each provide detailed summaries of known vulnerabilities and solutions. Once I was comfortable with the process, it became easy to identify false positives.
  
- For this assignment, I identified applicable areas of security, conducted a manual inspection of the code base, conducted a Maven dependency check to determine vulnerabilities, and developed a mitigation plan. In the future, I would use each of these techniques including suppressing any existing false positives.
  
- To ensure the code and software application were functional and secure, I had to re-run the maven configuration that I set up in the beginning. If the build was successful, it generated a new HTML dependance check report. I compared the new report to the original report, checking to see if there were any new vulnerabilities. I frequently visited helpful websites such as StackOverFlow, and as mentioned before, the CVE and NVD databases for security vulnerability information.

- From this particular project, I want to showcase my ability to generate self-signed certificates using the Java Keytool.

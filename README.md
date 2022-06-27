# CS-305

- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  - Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their clients. The organization has a RESTful web application programming interface (API) and needs protection from external threats. My role was to identify any security vulnerabilites within their existing software.

- What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  - I did well with testing the code base, and identifying security vulnerabilities using the CVE and NVD databases. It is important to code securely because it helps remove commonly expolided software vulnerabilities, which keeps business and their users safe from attacks. The value that software security adds to a company's overall wellbeing is the users trust.
  
- What about the process of working through the vulnerability assessment did you find challenging or helpful?
  - I found it helpful to use the CVE and NVD databases because they each provide detailed summaries of known vulnerabilities and solutions. Once I was comfortable with the process, it became easy to identify false positives.
  
- How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
  - For this assignment, I identified applicable areas of security, conducted a manual inspection of the code base, conducted a Maven dependency check to determine vulnerabilities, and developed a mitigation plan. In the future, I would uses each of these techniques including suppressing any existing false positives.
  
- How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?  
  - To ensure the code and software application were functional and secure, I had to re-run the maven configuration that I set up in the beginning. If the build was successful, it generated a new HTML dependance check report. I compared the new report to the original report, checking to see if there were any new vulnerablilities.
  
- What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
  - I frequently visited helpful websites such as StackOverFlow, and I used the CVE and NVD databases for security vulnerability information.

- Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
  - From this particular assignment, I would want to showcase my ability to generate self-signed certificates using the Java Keytool.

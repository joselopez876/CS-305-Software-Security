# CS-305-Software-Security
- Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for its customers. Their financial plans include savings, retirement, investments, and insurance. To protect customer and financial data while it was in transit and at rest, Artemis Financial wanted to enhance the security of its web application. Specifically, they requested a file verification step by using a checksum to ensure a secure data transfer.

- What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
It is important to code securely to reduce the risk of creating more vulnerabilities or exploits. If the code is not written for security the chance of a breach is more than likely. It adds value to a company by mitigating the risks of being attacked. This builds customer trust and lowers the costs associated with potential security breaches. Software security is crucial for long-term success, which is greater than the short-term success gained when taking shortcuts in code.

- Which part of the vulnerability assessment was challenging or helpful to you?
In the vulnerability assessment the part I found the most challenging was identifying and suppressing false positives. These false positives can be difficult to detect but once suppressed they can save a lot of time in a project. They can take you into a deep dive into a problem that is not even there.
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To increase layers of security, I implemented encryption algorithms to secure data in transit and at rest.  I also created an SSL certificate to encrypt communication between the client and the server. There is also a file verification using a checksum to ensure data is clean. Lastly, I secured HTTP POST requests ensuring that sensitive data is sent in the request rather than the URL. All of this together provides an extra layer of protection that minimizes the risk of data breaches and unauthorized access. In the future, I would want to ensure the entire system is scanned to identify real vulnerabilities vs false positives. 

- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code I had to run the program several times and perform dependency checks to make sure no new vulnerabilities were introduced. This step ensured that the code was functional and secure. 

- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The Java Keytool, dependency check, and Eclipse IDE resources that I know I will be using in the future. The Keytool will help me manage security certificates and keystores, while Dependency Check ensures my projects are free from known vulnerabilities. The Eclipse IDE will be a primary tool for coding, debugging, and projects.

- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
In this assignment, I've shown that I can identify and mitigate software vulnerabilities effectively. I implemented encryption algorithms and showcased my secure coding practices in an application that runs without errors. Also, I showed strong communication skills by clearly documenting and presenting the work I completed. This is a huge skill that can be often overlooked but is important in a collaborative environment.

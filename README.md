# CS305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis financial wanted to increase their security by having file uploads validated. Their interface is a public web interface so they wanted to make sure it was secure.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think the key generation was particularly well and the checksum. I learned the most with key generation and management since I had to partially reverse engineer some of the older projects around managing the keystore. Software security is a risk mitigation and cost mitigation procedure. By practicing safety you ensure that data and communication stays safe and away from prying individuals and prevent cost that would be generated from lawsuits and recovery of data. There's also an added benefit of consumer confidence.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
Definitely the key management. I had to review the old project and go through more detail to determine how to get the key to setup correctly. So it was both challenging, but I solidified more of the process due to the challenege.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
The first approach was to determine what the requirements were and what the potential vulnerabilities in the requirements are. The technique or stratgies to employ would be the vulnerability assessment process flow to identify what might need to be enhanced for security needs.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
The OWASP dependency check was ran twice. Once before and once after code changes to ensure nothing new was added in terms of vulnerabilities. There was also a manual code review to see if there was a vulnerability added after the fact such as allowing user input to manipulate the new code. There wasn't any way for the user to manipulate anything so all was secure.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
The dependency tool was the most useful since it helps connect you to all of the collective work of other software security engineers. A resource I would use more often would be things such as the security publications referenced and the JAVA secure guidelines (https://www.oracle.com/java/technologies/javase/seccodeguide.html).

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I think that topics 1 Algorithm Cipher, 2 Certification Generation, 3 Deploying a cipher, and 4 the secure communications are the most impactful. It shows more of a direct approach to security. Further topics include more secondary items that are equally important but seem to do more with reporting and a collection of knowledge than intimate understanding.

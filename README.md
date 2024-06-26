Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that is in charge of a variety of different accounts which include savings, retirement, investments, and insurance. In particular, they wanted to make sure that data sent to and from their servers was both encrypted, and cryptographically verifiable.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
For the cryptographic hash function used to verify data integrity, I chose SHA3-256, one of the most powerful and advanced cryptographic algorithms currently available. I also created code that performs a hash function on any given input data and displays the resulting checksum. My code is clean and efficient, and it provides features that will help companies keep their data safe.

What part of the vulnerability assessment was challenging or helpful to you?
I found the knowledge I gained from researching how to mitigate vulnerabilities to be very helpful. When developing a program, it is interesting to study which versions are safe. While some versions have bug fixes, they also have their own bugs. Therefore, finding exactly which version is safest to use can be a challenge.


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
First, I determined what Artemis Financial wanted out of the project and what type of attack was the biggest threat to them. It is important for financial institutions to keep their customers and their customer information as secure as possible. Therefore, protecting apis, clients/servers, encapsulating data, error handling, encryption, and code quality are all important elements of the Artemis Financial project. Also, when developing a program, I will always run a dependency check to determine if there are any security holes in the program. False positives are always possible, so it's important to suppress them when identifying the dependencies that really need to be mitigated. This saves time and allows me to focus on securing other parts of the program.


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
By performing dependency checks and refactoring obvious errors in the code, I was able to identify defects in the code and improve them. I rerun the dependency check to see if there are any new vulnerabilities when refactoring the code.


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Reading the rubric carefully and the resources in the module really help out when it comes to doing assignments at SNHU．



Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show them that I understand how important secure coding is and how refactoring code is an important skill to learn.

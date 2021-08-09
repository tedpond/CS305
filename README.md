# CS305


    Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
    
    Artemis Financial is a financial institution that specializes in consultation and develops fincnial plans for savings, retirement, investements and insurance for the end user. They require safe and secure software that is current and implements the RESTful web API to bridge client to end user communications. They are requesting Global Rain to assist in the creation of that custom software and ensure that it is resistent to attacks to security vulnerabilities.
    
    What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
    
    I found that the implementation of the AES-256 algorithm and subsequently the SHA-256 hash algorithm to be a great addition to the security of the software required by Artemis Finicial. I believe that it is important to code securely because it is a mindset that we must adopt so that we do not have to backtrack to add security features in post. It ensures that the company can be trusted by its clients and end users, which grants peace of mind to consumers.
    
    What about the process of working through the vulnerability assessment did you find challenging or helpful?
     
     I found that the vulnerability assessment, especially the vulnerability assessment flow diagram, to be very vague. There are not very many resources on it and it is generally up to interpretation. To that end, it makes sense to be vague, since new and challenging vulnerabilities are always on the rise.
    
    How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
    
    If you consider that a hacker will always get their way in the end. We have to adopt the mindset, that it might not be perfect protection, but it is a hindrance to the hacker. More layers of security means that that is another layer that the hacker has to defeat. For example, using an AES-256 bit encryption will force the hacker to use a brute force attack that will take many many years. I believe that the usage of methods that slow down attackers, no matter what that might be is a good way of increasing the security of a piece of software.
    
    How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
    
    I ensured the code and software application were functional by actually running the code. I tried accessing it using other methods and in each case, it would fail to grant me access without the proper authentication and validation. This was as simple as trying to access the code through https vs http, using different ports, accessing without the proper P-12 certification, etc...
    
    What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
    
    The use of a input validation is a useful tool that helps with making sure that we limit the threat of buffer overloads and buffer side attacks. We can also easily add comments to increase the readability of code, which decreases the chance of human error.
    
    Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
    
    The use of AES-256 encryption, SHA hashing, and static vulnerability testing.

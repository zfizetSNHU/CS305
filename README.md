# CS305


    Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

    Artemis Financial is a banking institution that handles monetary transactions like withdraws, deposits, and etc. For this particular project, I was tasked with addressing security concerns and making recommendations to ensure that their software was secure.
    
    What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

    Its important to code securely because coding securely "now" will prevent issues that may arise "later". Additionally, coding securely will protect both users when using the product and the company from liability, especially when handling sensitive personal information such as banking information.
    Software security ensures that the company is following any established legal guidelines when developing software, such as HIPPA or certain banking regulations depending on country/region. A company that doesn't follow these regulations can find itself in a mountain of legal trouble.
    When I found my client's security vulnerabilities, I recommended a certain algorithm cipher they should employ, as well as industry best practices to follow when developing secure software.
    
    Which part of the vulnerability assessment was challenging or helpful to you?

    The most challenging aspect of the project was figuring out how to get a self-gen certificate to cooperate with internet browsers to "trust" the connection between the application and the user. After doing a bunch of personal research on the subject, I believe that I solved the issue,
    but it was easily the longest part of troubleshooting that I experienced when developing this software.
    
    How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

    I deployed a AES-256 algorithm cipher into the application, as well as enabled SSL within the application, ensuring safe and secure connections for users and the server. To assess vulnerabilities, I would continue to use a vulnerability assessment report to help highlight some of the potential security threats
    that the application might have and then investigate further on how to mitigate said threats. I would continue to use a secure cipher, depending on the situation, as something like AES-256 is very secure and virtually impossible to brute force.
    
    How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

    I ensured that I was following secure coding guidelines and not adding any additional vulnerabilities into the software. This included not adding more than was necessary to the project, as adding "too much" than what was needed to operate could increase the potential for a vulnerability to arise. 
    After refactoring the code, I ran a vulerability check and reviewed the assessment that was generating afterwards, ensuring to check for any false positives and addressing each vulnerability as necessary.
    
    What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

    W3Schools has an incredible library of resources that I utilize for almost every CS course that I have taken so far. I find that having these quick links to certain outlines or logic to be helpful when I get stuck on a problem or need assistance figuring out how to approach a problem.
    
    Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

    From this assignment, I would show that I can successfully deploy an algorithm cipher and generate certificates - as I feel that both of these things are essential when developing almost any modern software.

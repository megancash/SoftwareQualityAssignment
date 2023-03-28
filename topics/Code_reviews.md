# **Code Reviews**

## What are code reviews?
- Code reviews play an important part in making sure high quality of code for the application. Other developers assess the code and functions written by a software developer during these reviews.

- These reviews make sure to identify bugs, improve the code quality, improve security, ensure efficiency, and facilitate learning for new developers working with the code. This is an essential part in the software development process. Code reviews are conducted once a developer completes programming to receive a second opinion on the solution and implementation. 

•   Typically, this review is conducted before merging the code into an upstream branch, it serves as an additional layer of scrutiny for identifying bugs, logic problems, uncovered edge cases, or other issues. 

•   To ensure effective code reviews, the reviewer should have some expertise in the technology or program used. If the code covers more than one domain it is possible to bring in more developers to help review the code.

https://about.gitlab.com/topics/version-control/what-is-code-review #:~:text=Code%20reviews%2C%20also%20known%20as,developers%20learn%20the%20source%20code

## Tools for code reviews
o   Tools for code reviews can be helpful for collaboration while maintaining the uniformity and quality of the code. 

o   These technologies can assist the team members communicate faster and more easily, document the process, keep track of all that is needed to be accomplished, as well as giving the review process structure. 

o   GitHub is an example of a code review tool. It is the most popular and taught in many universities and colleges throughout the world. Therefore, many software developers will already know this technology. 
   It has many features, catering to specific use case scenarios and helps at different stages of the programming life cycle. The tool integrates well with third party services and works well with Microsoft tools. 
   An aspect it lacks, is only supporting GitHub hosted git repos. Features like version control may also be too complex for developers getting started learning this technology. 

o   CodeScene is another example of a code review tool. 
   The core of this product is using algorithms to find bugs and issues in the application. 
   Downsides of the product is the complexity of learning this tool for effective use. 

o   A final example would be Gerrit. 
   Which is a free tool that merges the functions of a review tool and bug tracking.
   An issue with this tool would be not having clear documentation to be able to learn this technology effectively.
https://crocoblock.com/blog/best-code-review-tools/

## Process for  code Review 
•   The most important factors to be considered for Code Reviews are design, functionality, complexity, tests, naming, comments, style, and consistency. 

•   For design, it should be considered how different functions and objects are connected to each other and if that makes sense logically. How the added code fits with the existing code. 

•   To consider functionality, ensure the added code works as the programmer planned for. Make sure it doesn’t harm the end customer using the program. 

•   Complexity is another factor to consider, this highlight’s if there is a simpler method to adding the feature. Things to consider for complexity would be, is the application being overengineered? Will other engineers be able to understand the added code and build other programs on top of it?

•   Reviewers should also evaluate the tests included in the changed code to ensure they are appropriate and useful. Additionally, reviewers should check whether the developer used good names and wrote clear comments that explain the reasoning behind the decisions made.

•   Tests are an aspect to work on with code reviews. It focuses on having appropriate and well structed testing for code. It is possible to automate with  this process with a tool like Selenium. 

•   Finally, reviewers should ensure that changed code follows the appropriate style guide and is consistent with existing code. The naming and comments are consistent with the project. All the changes of the code should be put into documentation. 

•   By examining these factors during a code review. The reviewer can make ensure the code is of high quality, maintainable, and meets the needs of the end-users and for future developers.
https://google.github.io/eng-practices/review/

Best Practices 
•   Understand what to examine in the code review, the code added should perform a feature or part of a feature. 
o   Identify the feature and then how possible mistakes can arise from this feature. In case of finding bugs or edge cases that break the program. 
o   It is essential to have a process or steps to solve these issues.

•   Secondly automate tests that is possible to be automated, this will be essential to save time for the reviewer and focus on other aspects of the review. 

•   It's important to remember the significance of keeping code reviews short. 

o   A suggested guideline for the review duration is between 30 and 60 minutes.

o   While another suggestion is to review only 100 to 300 lines of code. 

o   It is also important to provide constructive feedback rather than being overly harsh to ensure positivity and high morale.
https://www.futuremind.com/insights/what-is-code-review-and-how-to-perform-one

•   Types of Code Reviews 
•   There are different ways to conduct a code review, including pair programming, over-the-shoulder review, and tool-assisted review. 
•   Pair programming involves two developers working together on the same code in real-time. 
o   This means one programmer writes code and another programmer reviews the code. 
o   It is more suited for very complex systems that might need more than one person working on it at a time. 
o   Disadvantages of this system include how inefficient this process is. 

•   Over the shoulder review is quick and informal method. 
o   This is where a developer shows their laptop or computer with their code written to another developer and they review it together.
o   A drawback to this method would be the lack of documentation and this would in turn effect the quality of code reviews in the long run. 

•   Tool-assisted review is the most effective method as it uses software-based code review tools to replace many functionalities including:

o   In person meeting 
o   Helps keep track of comments.
o   Changes made in the code.
o   Version control.
o   Provide metrics for commits.

https://swimm.io/learn/code-reviews/code-reviews-pros-and-cons-approaches-tools-and-tips/

What is logging?
•   Logging in computing refers to the process of keeping logs of events that might occur during the development of an application. These events can range from errors, problems, changes or just messages related to the task at hand. An article on CodeProject describes logging as “the process of recording application actions and state to a secondary interface” (Eberhardt, 2014). 
•   Logs typically facilitate debugging. 
•   When working on a project, one should be logging consistently because the practice can often decide whether a task is successfully completed by an application.
•   Eberhardt’s article goes into more detail about what logging is, and the importance of logging in computing. 
•   Link:
 https://www.codeproject.com/Articles/42354/The-Art-of-Logging#what
•   Here is an example of a log file with timestamps and messages: 
 

Error logs:
•   Error logs, more specifically, contain records of errors that programs may run into while executing. 
•   These records usually contain timestamps, criticality levels and descriptions all related to the error. 
•   There are two types: unhandled error messages and custom error messages. 
•   It is important to note that error logging is an ambiguous term – application error logs can also contain messages that aren’t errors. 
•   It is important for error logs to be of a high quality so that they can provide users with critical information about problems such as what happened, when and where the error occurred, and usually a trace ID to connect to other events. 
•   Error logging is beneficial because besides making the project development process easier, they can lead to improvements in project performance and resolution times.
•   You can read more about the contents of error logs here: https://www.crowdstrike.com/cybersecurity-101/observability/error-logs/

How to make the most of error logs:
•   There are a number of ways in which you can both improve and make the most of your error logs. Including thread names, classes and line numbers for errors is a basic measure that can prove to be beneficial. 

•   When working with custom error logs (logs that you are creating or implementing for an application by yourself), you could set an appropriate warning level with each message to notify developers of the severity of the error. 

•   Having a set standard or structure for error logs proves useful to developers because they’ll know what to expect and can look out for keywords that relate to the errors.

•   Tracing can be utilized in logging to make the process of backtracking a user’s actions easier. 

•   A developer could create a unique identifier inside of the error messages for users of an application to make it easier to see where certain errors might have occurred. 

•   For more information on how to improve error logs, read this article by Chris Cooney: https://coralogix.com/blog/10-things-that-will-take-your-error-logs-up-a-level/



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

# **Code Reviews**

## What are code reviews
- Code reviews play an important part in making sure high quality of code for the application. Other developers assess the code and functions written by a software developer during these reviews.

- These reviews make sure to identify bugs, improve the code quality, improve security, ensure efficiency, and facilitate learning for new developers working with the code. This is an essential part in the software development process. Code reviews are conducted once a developer completes programming to receive a second opinion on the solution and implementation. 

- Typically, this review is conducted before merging the code into an upstream branch, it serves as an additional layer of scrutiny for identifying bugs, logic problems, uncovered edge cases, or other issues. 

- To ensure effective code reviews, the reviewer should have some expertise in the technology or program used. If the code covers more than one domain it is possible to bring in more developers to help review the code.

**Link:**

- [Code Review](https://about.gitlab.com/topics/version-control/what-is-code-review)  



## Tools for code reviews
- Tools for code reviews can be helpful for collaboration while maintaining the uniformity and quality of the code. 

- These technologies can assist the team members communicate faster and more easily, document the process, keep track of all that is needed to be accomplished, as well as giving the review process structure. 

- GitHub is an example of a code review tool. It is the most popular and taught in many universities and colleges throughout the world. Therefore, many software developers already know this technology. 
    -   It has many features, catering to specific use case scenarios and helps at different stages of the programming life cycle. The tool integrates well with third party services and works well with Microsoft tools. 
    -   An aspect it lacks, is only supporting GitHub hosted git repos. Features like version control may also be too complex for developers getting started learning this technology. 

- CodeScene is another example of a code review tool. 
    -   The core of this product is using algorithms to find bugs and issues in the application. 
    -   Downsides of the product is the complexity of learning this tool for effective use. 

- A final example would be Gerrit. 
    -   Which is a free tool that merges the functions of a review tool and bug tracking.
    -   An issue with this tool would be not having clear documentation to be able to learn this technology effectively.

**Link:**

- [Tools for Code Review](https://crocoblock.com/blog/best-code-review-tools/)



## Process for  code Review 
- The most important factors to be considered for Code Reviews are design, functionality, complexity, tests, naming, comments, style, and consistency. 

- For design, it should be considered how different functions and objects are connected to each other and if that makes sense logically. How the added code fits with the existing code. 

- To consider functionality, ensure the added code works as the programmer planned for. Make sure it doesn’t harm the end customer using the program. 

- Complexity is another factor to consider, this highlight’s if there is a simpler method to adding the feature. Things to consider for complexity would be, is the application being overengineered? Will other engineers be able to understand the added code and build other programs on top of it?

- Reviewers should also evaluate the tests included in the changed code to ensure they are appropriate and useful. Additionally, reviewers should check whether the developer used good names and wrote clear comments that explain the reasoning behind the decisions made.

- Tests are an aspect to work on with code reviews. It focuses on having appropriate and well structed testing for code. It is possible to automate with  this process with a tool like Selenium. 

- Finally, reviewers should ensure that changed code follows the appropriate style guide and is consistent with existing code. The naming and comments are consistent with the project. All the changes of the code should be put into documentation. 

- By examining these factors during a code review. The reviewer can make ensure the code is of high quality, maintainable, and meets the needs of the end-users and for future developers.

**Link:**

- [Process for Code Review](https://google.github.io/eng-practices/review/)



## Best Practices 
- Understand what to examine in the code review, the code added should perform a feature or part of a feature. 
    -   Identify the feature and then how possible mistakes can arise from this feature. In case of finding bugs or edge cases that break the program. 
    -   It is essential to have a process or steps to solve these issues.

- Secondly automate tests that is possible to be automated, this will be essential to save time for the reviewer and focus on other aspects of the review. 

- It's important to remember the significance of keeping code reviews short. 
    -   A suggested guideline for the review duration is between 30 and 60 minutes.
    -   While another suggestion is to review only 100 to 300 lines of code. 

- It is also important to provide constructive feedback rather than being overly harsh to ensure positivity and high morale.

**Link:**

- [Best Practices](https://www.futuremind.com/insights/what-is-code-review-and-how-to-perform-one)



## Types of Code Reviews 
- There are different ways to conduct a code review, including pair programming, over-the-shoulder review, and tool-assisted review. 

- Pair programming involves two developers working together on the same code in real-time. 
    -   This means one programmer writes code and another programmer reviews the code. 
    -   It is more suited for very complex systems that might need more than one person working on it at a time. 
    -   Disadvantages of this system include how inefficient this process is. 

- Over the shoulder review is quick and informal method. 
    -  This is where a developer shows their laptop or computer with their code written to another developer and they review it together.
    -  A drawback to this method would be the lack of documentation and this would in turn effect the quality of code reviews in the long run. 

- Tool-assisted review is the most effective method as it uses software-based code review tools to replace many functionalities including:
    -  In person meeting 
    -  Helps keep track of comments.
    -  Changes made in the code.
    -  Version control.
    -  Provide metrics for commits.

**Link:**

- [Types of Code Reviews](https://swimm.io/learn/code-reviews/code-reviews-pros-and-cons-approaches-tools-and-tips/)



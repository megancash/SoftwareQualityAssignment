# **Error Logging** 

 

## What is logging? 

- Logging in computing refers to the process of keeping logs of events that might occur during the development of an application. These events can range from errors, problems, changes or just messages related to the task at hand. An article on CodeProject describes logging as “the process of recording application actions and state to a secondary interface”.  

- Logs typically facilitate debugging.  

- When working on a project, one should be logging consistently because the practice can often decide whether a task is successfully completed by an application. 

- Eberhardt’s article goes into more detail about what logging is, and the importance of logging in computing.  

 

**Link:** 

 

- [Logging] (https://www.codeproject.com/Articles/42354/The-Art-of-Logging#what) 

 

 

  

## **Error logs** 

- Error logs, more specifically, contain records of errors that programs may run into while executing.  

- These records usually contain timestamps, criticality levels and descriptions all related to the error.  

- There are two types: unhandled error messages and custom error messages.  

- It is important to note that error logging is an ambiguous term – application error logs can also contain messages that aren’t errors.  

- It is important for error logs to be of a high quality so that they can provide users with critical information about problems such as what happened, when and where the error occurred, and usually a trace ID to connect to other events.  

- Error logging is beneficial because besides making the project development process easier, they can lead to improvements in project performance and resolution times. 

- [You can learn more about the contents of error logs here](https://www.crowdstrike.com/cybersecurity-101/observability/error-logs/) 

 

 

 

## **How to make the most of error logs** 

- There are a number of ways in which you can both improve and make the most of your error logs. Including thread names, classes and line numbers for errors is a basic measure that can prove to be beneficial.  

 

- When working with custom error logs (logs that you are creating or implementing for an application by yourself), you could set an appropriate warning level with each message to notify developers of the severity of the error.  

 

- Having a set standard or structure for error logs proves useful to developers because they’ll know what to expect and can look out for keywords that relate to the errors. 

 

- Tracing can be utilized in logging to make the process of backtracking a user’s actions easier.  

 

- A developer could create a unique identifier inside of the error messages for users of an application to make it easier to see where certain errors might have occurred.  

 

- [For more information on how to improve error logs, read this article by Chris Cooney](https://coralogix.com/blog/10-things-that-will-take-your-error-logs-up-a-level/) 

 

 

 

## **Challenges with logging** 

 

- There are some notable challenges that come with managing error logs.  

- For one, when looking for specific error messages, it can be difficult for developers to differentiate between them going off keywords such as “ERROR” and “FATAL” as they lack context as to the details of the specific error in question, and at times can often be misleading.  

- Some “FATAL” errors can be fixed with a minimal number of changes, while others might require more.  

- Another challenge that could arise with logging could be the volume of logs that may appear at any given time. Not having a clear tracking path towards the error in question can complicate the process of resolving the issue.  

- [This article goes into more detail about the challenges one might face while analyzing logs](https://queue.acm.org/detail.cfm?id=2082137) 

 

 

 

## **Good Practices** 

 

- An article on LoomSystems by Liron Tal describes some common good error logging practices such as: knowing who or what will be using your logs (humans or machines) and making them easy to translate, understanding the metrics being used in log messages (such as time as we mentioned earlier), providing context for log messages so developers or users will make only the required changes in their approach, and even optimizing alerts and exception handling by utilizing certain tools like Apache ExceptionUtils to condense and make the stack trace more translatable.  

- [You can read about some of the best logging practices here](https://www.loomsystems.com/blog/single-post/2017/01/26/9-logging-best-practices-based-on-hands-on-experience) 
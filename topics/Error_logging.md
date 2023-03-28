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
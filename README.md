# FogBugz-Logging-WPA

Logging exceptions of Windows Phone applications to a central server with the help of FogBugz

I would like to share the experiences that our company has gained about Windows Phone Marketplace with the community.

## Background

All Windows Marketplace applications must meet the conditions imposed by Microsoft (Technical Certification Requirements). One of those items is the exclusion of 'Unhandled Exceptions'. To get our application out to the market, it must not close as a result of an unhandled exception. It is pointed out in the following regulation:

### 5.1.2. Application Closure

The application must handle exceptions raised by the .NET Framework and not close unexpectedly. During the certification process, the application is monitored for unexpected closure. An application that closes unexpectedly fails certification. The application must continue to run and remain responsive to user input after the exception is handled.

However, the fact that we show "friendly" face to the users when unhandled exceptions occur, in fact, it is only symptomatic treatment. In any case, if a similar situation occurs while using the application, our application will cause an unhandled exception. The real answer is if the developer is informed about this problem, and so with further development of the application they will avoid the exception. To do this information is needed about runtime unhandled exceptions. There are many possibilities for this...

[read more...] (http://www.codeproject.com/Articles/412435/Logging-exceptions-of-Windows-Phone-applications-t)

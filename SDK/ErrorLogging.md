#   Logging

If you want to send data to the application log of an application, you can do so by calling the Log method of the [GDPRCore.Current]() property.

##  Local vs Core

In order to test your applications, you can implement a local [GDPRCore]() class that will redirect to a log file for testing purposes.
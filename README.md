# psr-loggers
Classes that implement psr/log LoggerInterface, useful for testing or wrapping other loggers for extra features

* EchoLogger - Just echos out the logs
* MockLogger - Does nothing, useful for testing. 
* ContextLogger - Wraps an existing logger then allows you to set some extra context on the logger that will be added to every log output. 

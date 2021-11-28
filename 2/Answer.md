Mention 10 best practises when logging. Why is log formatting necessary?

    Good logging practice:
        Always keep date in your log file name
        Always add some name to your log file name. It will help you in the future to distinguish log files from different instances of your system.
        Always log time and date (preferably up to milliseconds resolution) for every log event.
        Always store your date as YYYYMMDD. Everywhere. In filename, inside of logfile. It greatly helps with sorting. Some separators are allowed (eg. 2009-11-29).
        In general avoid storing logs in database. In is another point of failure in your logging schema.
        If you have multithreaded system always log thread id.
        If you have multi process system always log process id.
        If you have many computers always log computer id.

    - Choose Your Goals
        While logging is required to maintain your network healthy and operational, you can also utilize it for analytics and profiling. Whatever you intend to do with your logs, you must first establish these objectives. These goals can then be used as a reference point for deciding on the rest of your logging and monitoring best practices, as well as creating logging standards for your entire organization

    - Follow Logging Standards
        Using what has already been standardized for you is a fantastic place to start. Instead of manually reading and analyzing individual logs, use a standard logging framework. This provides built-in tools for controlling the amount of detail in logs, defining alert severity levels, and implementing log rotation policies, as well as community support for troubleshooting. You'll discover that following log monitoring and generation guidelines makes your job a lot easier.
    - Make Your Logs Accessible
        All logging practices have a human and a machine audience. Humans cannot handle or sort through the vast volumes of data that come through the logging process, whereas computers are swift and efficient at dealing with massive amounts of structured data. People, on the other hand, have the advantage of being able to analyze unstructured data well, which can aid in the detection of problems (with the right tools). To ensure that your log messages can be read and used successfully by your IT team, use the following logging practices: 

            Select a standard date and time format. 
            Make sure the timestamps are in local time (or UTC) with an offset. 
            Make sure your log levels are set correctly. 
            Wherever possible, provide context to logs.
    - Make Sure Your Logs Are Helpful
        In an emergency, log messages are often the only way to figure out what went wrong with the system and how to troubleshoot it efficiently. Separate from the code or other messages, make sure you understand what the log messages refer to and where area of your network has been impacted. Keep a record of potential troubleshooting information for each portion of your network whenever possible, so that if a problem arises, you'll already know what the device or application's purpose is and what the log message means to your end users.
    - Create Logging Standards and Structure
        Creating logging standards, so that all of the logs you get follow a uniform structure, is one of the greatest tactics for optimizing your logging procedures. Ensure that all logs include a timestamp as well as the host and logger's names. Event or user IDs, application versions, and metrics are all examples of useful data. Finally, you may assign unique tags or IDs to log lines, making it easier to trace down problems or determine when the same event has occurred multiple times.
    - Use Error Severity Levels
        For troubleshooting or network monitoring, not all events are equal, and being able to distinguish serious events from irregular or routine logs is vital. All logs for all devices should include statements like FATAL, ERROR, WARN, INFO, DEBUG, TRACE, ALL, or OFF, as well as logging levels like FATAL, ERROR, WARN, INFO, DEBUG, TRACE, ALL, or OFF. If logs were set up without these notifications, this will need to be fixed right away.
    - Find the Middle Ground in Detail
        When configuring what kind of information your logs provide, you'll want to strike a balance between the level of detail your log messages show and the amount of information they provide. Even if you have a technology in place, if your log messages contain too little or too much information, you may become overwhelmed or miss something important. The logs should provide enough information to diagnose the problem, but not so much that you can't perceive what's going on in a broad sense.
    - Use a Tool for Management
        Even when following all best practices, logging and monitoring, especially for bigger networks and databases, remains a demanding undertaking. Manually going through logs during an emergency is inefficient, slow, and stressful. To make your job easier, I propose utilizing an appropriate tool.

Why is log formatting necessary?
    A log format is a structured format for making logs machine-readable and parsable. This is the power of structured logs and a log management system that can handle them. One of the most important characteristics of log management software is the ability to convert raw data into something that is immediately understandable and easy to read.

    The JSON (JavaScript Object Notation) format is a highly readable data-transfer format that has become the industry standard for structured logging. It's small and light, and it's easy to read and write for both humans and robots. It can be parsed by almost all programming languages, including those without built-in JSON support. Because of its Unicode encoding, JSON is a universal format that can be used on any platform, including PCs, Macs, and servers.

    For log management and monitoring, JSON logging is a must. This format is frequently favored over plain text because it allows for the creation of field-rich databases that can be searched later. JSON logs are more detailed than most other log formats, and they're popular for structured logging since they can easily be enhanced with additional context and metadata.

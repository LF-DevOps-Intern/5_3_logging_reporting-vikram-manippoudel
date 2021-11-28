> Whether you're collecting logs for application security and compliance, production monitoring, performance monitoring, or troubleshooting, they're full with useful information about your apps' health. But it all boils down to what you log and how you log it, which is where log management software comes in. Log centralization and analysis provide a real-time perspective of how your users interact with your applications and systems, as well as deeper insights and possibilities to enhance code quality, increase efficiency, minimize risks, and provide a better customer experience.

> Datadog is a SaaS that started up as a monitoring (APM) tool and later added log management capabilities as well. You can send logs via HTTP(S) or syslog, either via existing log shippers (rsyslog, syslog-ng, Logstash, etc.) or through Datadog’s own agent. It features Logging without Limits™, which is a double-edged sword: harder to predict and manage costs, but you get pay-as-you-use pricing (see below) combined with the fact that you can archive and restore from archive.

    Key Features:
        Server-side processing pipeline for parsing and enriching logs
        Automatically detects common log patterns
        Can archive logs to AWS/Azure/Google Cloud storage and rehydrate them later



> LogDNA is a newer player in the log management space. Available as both SaaS and on premises, LogDNA provides all the logging basics: agent-based and agentless log collection, via syslog and HTTP(S) plus full-text search and visualizations, with clear and competitive pricing.

    Key Features:
    Embedded views to share logs outside the organization
    Automatically parses common log formats


> Sematext Logs is a log management tool that exposes the Elasticsearch API, part of the Sematext Cloud full-stack monitoring solution. You can send data using syslog or any tool that works with Elasticsearch, such as Logstash or Filebeat. Visualizing can be done with Kibana or the native Sematext Logs UI. If you prefer a self-hosted solution, Sematext Logs is also available via Sematext Enterprise, the on-premise service.Sematext’s auto-discovery of logs and services lets you automatically start monitoring logs and forwarding them from both log files and containers directly through the user interface.

    Key Features:

    Agent-free: any log shipper or library that works with syslog or Elasticsearch will work with Sematext Logs
    Elasticsearch API access beyond indexing: you can run searches, export data, create custom templates, and more
    Extra features on top of the ELK stack are available, such as role-based access control, alerting, and anomaly detection

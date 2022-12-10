#Post Mortem

##Issue Summary

On December 10, 2022, from 10:00 AM to 11:00 AM PST, there was an outage affecting the web-01 server, which caused the AirBnB_clone_v2 website to become unavailable to users. The outage affected approximately 100% of users who were trying to access the website during this time.

The root cause of the outage was a hardware failure in the web-01 server, which caused the server to become unresponsive and unable to serve web requests.

##Timeline

10:00 AM PST: The issue was detected when the monitoring system alerted the on-call engineer that the web-01 server was unresponsive and unable to serve web requests.

10:05 AM PST: The on-call engineer logged into the web-01 server and attempted to restart the web server software, but the server remained unresponsive.

10:10 AM PST: The on-call engineer escalated the issue to the operations team, who began investigating the root cause of the outage.

10:15 AM PST: The operations team assumed that the issue was caused by a software problem and began investigating the web server logs and configuration files.

10:25 AM PST: After further investigation, the operations team realized that the issue was not caused by a software problem, but rather by a hardware failure in the web-01 server.

10:30 AM PST: The operations team escalated the issue to the engineering team, who began working on replacing the failed hardware in the web-01 server.

11:00 AM PST: The engineering team successfully replaced the failed hardware and the web-01 server was brought back online.

##Root Cause and Resolution

The root cause of the outage was a hardware failure in the web-01 server, specifically in the server's hard drive. The hard drive failed, causing the server to become unresponsive and unable to serve web requests.

To resolve the issue, the engineering team replaced the failed hard drive with a new one, and the web-01 server was brought back online.

##Corrective and Preventative Measures

To prevent this issue from happening again in the future, the following corrective measures will be taken:

The web-01 server will be configured to automatically failover to a standby server in the event of a hardware failure.
The operations team will regularly monitor the health of the web-01 server's hardware and proactively replace any components that are showing signs of failure.
The engineering team will implement regular scheduled maintenance to ensure that all hardware components are in good working order.
##Tasks to address the issue:

Configure automatic failover for the web-01 server
Monitor the health of the web-01 server's hardware
Schedule regular maintenance for the web-01 server's hardware

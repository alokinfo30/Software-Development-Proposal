# Software-Development-Proposal : Real-Time Manufacturing Status Dashboard (For Daikibo’s Telemetry Live Dashboard)
 
1. Overview
Daikibo Industrials requires a unified, high-reliability solution to monitor its global manufacturing
footprint. Following the successful unification of telemetry data formats, the next strategic step is
the deployment of a Real-Time Manufacturing Status Dashboard.
This project aims to provide site managers and operations leadership with an instantaneous
overview of the health status of 36 critical machines (9 units across 4 factories). By transitioning
from offline data analysis to real-time monitoring, Daikibo will achieve faster incident response
times and improved operational transparency.

2. Scope of Work
The proposed solution is a high-performance, single-page web application optimized for internal
use. The core functionalities include:
● Intranet-Restricted Access: The dashboard will be hosted internally, ensuring that
sensitive manufacturing data remains within the Daikibo corporate network.
● Enterprise Authentication: Integration with Daikibo’s internal authentication server
(LDAP/Active Directory) to allow seamless SSO (Single Sign-On) using existing
company-wide credentials.
● Hierarchical Status View: A collapsible/expandable UI architecture:
○ Factory Level: High-level health summary for each of the 4 global locations.
○ Device Level: Individual status for all 9 machines per factory.
○ Historical Data: Detailed expansion at the device level to display a chronological
history of telemetry statuses and alerts.
● Real-Time Telemetry Processing: Utilizing the unified data format to update machine
status (Healthy, Warning, Critical) without requiring manual page refreshes

•	A private dashboard with health status of the 9 telemtry-enabled machines in each of Daikibo's 4 factories.
•	Access to the page happens only within Daikibo’s Intranet/VPN.
•	Authentication is synced to internal authentication server (users don't need to create an account). 
•	The dashboard consists of a single page, listing the current statuses of all monitored devices.
•	The view is collapsible/expandable at a factory level, as well as device level (showing history of statuses)
You can refer to the wireframe image located on the root for a visual reference. Please note this is not the final design, and it’s just a mock-up visual representation of the functionality. 


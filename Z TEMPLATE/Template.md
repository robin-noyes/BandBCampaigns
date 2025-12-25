# Template
### Author:Robin Noyes
## Summary of Event

## Tags

## Compatible Decks
Core Deck (v3), Core Deck plus IR Expansion, Cloud Security (v2), ICS/IoT, Trimarc, RedCanary, DenSecure, Huntress, DataDog

## Scenarios


### Initial Compromise
_**Something here_

### Pivot & Escalate
_**Something here_

### C2 & Exfil
_**Something here_

### Persistence
_**Something here_

## Procedures that Reveal the Attack Chain



## Written Procedures
* Card Name Here
	* Description Here
* Card Name Here
	* Description Here
* Card Name Here
	* Description Here
* Card Name Here
	* Description Here

## Procedure Success (explanations of why it worked)
### General Reasons
- Technical (Detection Adaptability, Deployment & Infrastructure Readiness, Data Quality & Log Integrity, Visibility & Scope Coverage, and Operational Maturity.)
	- VarProcedure found unauthorized/suspicious evidence of IP/commands/software/log deletion on the system.  This was found by correlating logs from multiple data sets EDR/Windows Logs/Firewall/Proxy/Server/UberAgent.  This allowed for finding patient zero to use in subsequent searches.
	- VarProcedure discovered suspect network/data/flow activity between two devices that warrant further investigation of ports and protocols used.
	- VarProcedure discovered system changes during off-hours/outside of scheduled maintenance windows, leading the team to dig deeper into changes made.
	- VarProcedure discovered the system had several unpatched vulnerabilities/vulnerable libraries in use.
	- VarProcedure discovered a portion of the attack due to recent signature/agent/module updates.

- Financial
	- VarProcedure  was successful due to the recent budget approval to collect/deploy additional tool/services/application/log sources across the environment.
	- VarProcedure  was successful due to the recent implementation of additional models/packages for the tool/service/application which allowed key features to be enabled.
	- VarProcedure was successful due to the recent hire of a SME on the specific tool.
	- VarProcedure worked due to the recent approval for additional collectors implemented in the branch/office/data center.
	-  VarProcedure SME has returned from training with new in-depth knowledge to share.

- Political
	-
	 
- Personnel
	- VarProcedure

### Procedure Success Explanations
-  Technical (Detection Adaptability, Deployment & Infrastructure Readiness, Data Quality & Log Integrity, Visibility & Scope Coverage, and Operational Maturity.)
	- VarProcedure successfully detected the attack because it adapted to the attacker’s change in TTPs through recent updates to detection logic and behavioral baselining.
	- VarProcedure successfully detected the attack because the agent and signatures were up to date, and the recent update was validated and applied without corruption.
	- VarProcedure worked effectively because the agent was deployed successfully, with full support for the operating system and device type, including legacy or critical assets.
	- VarProcedure performed as expected because the appliance/server was online, fully patched, and not undergoing maintenance at the time of the attack.
	- VarProcedure functioned properly because the data center was operational, ownership was clearly established, and systems were protected from accidental removal or decommissioning.
	- VarProcedure operated successfully because agents and logging mechanisms were not only installed but also thoroughly validated for alert logic, data quality, and completeness.
	- VarProcedure returned accurate results because the search parameters included all relevant CIDR ranges, including internal, external, and any cloud-based assets.
	- VarProcedure was completed successfully with help from a local user who was guided through the collection process despite limited or intermittent internet connectivity.
	- VarProcedure detected the activity because logs were consistently forwarded to the SIEM, and logging configurations—including syslog server settings—were properly maintained.
	- VarProcedure worked as expected because comprehensive procedural documentation and updated network/data flow diagrams accurately reflected all critical paths and dependencies.
	- VarProcedure succeeded because the agent had been installed for a sufficient period, allowing it to collect enough telemetry to establish a solid baseline for detection.
	- VarProcedure worked efficiently due to appropriate permissions and full visibility across the environment, with no delays caused by approval workflows or access issues.

- Financial (Licensing & Coverage Expansion, Procurement & Renewal Timelines, Strategic Investment Alignment, Skills & Talent Investment, Infrastructure & Performance Investment)
	- VarProcedure worked successfully because the budget was approved in advance to expand licensing for the tool/service/project/application across all required entities, including subsidiaries, remote offices, data centers, and contractor environments.
	- VarProcedure remained fully operational because the PO to renew the tool/service was processed promptly, ensuring no interruption in service or detection capability.
	- VarProcedure detected the issue effectively because the organization invested in the advanced package, which included all necessary features and capabilities for comprehensive coverage.
	- VarProcedure functioned as expected because there was clear prioritization and alignment between projects, avoiding conflicts and ensuring that tool implementation and logging strategies were fully supported and integrated.
	- VarProcedure was successful because funding was approved to hire and/or train a dedicated SME. The team now has the necessary expertise to perform accurate and timely analysis using the tool.
	- VarProcedure worked because logging levels were maintained at the necessary detail, and performance issues were mitigated through executive-approved upgrades to newer, more capable devices. Proactive investments ensured stability and data fidelity.

- Political (Hierarchy & Influence, Ownership & Accountability, Interdepartmental Alignment, and Timing & Prioritization, competition)
	- VarProcedure worked successfully because the Owner/VP/Project Manager aligned with the security team early in the planning phase, ensuring it was configured at the subsidiary/branch/business unit without impacting their critical project timeline. Cross-functional collaboration made the integration smooth.
	- VarProcedure was effective because the board approved the deployment project within the current fiscal year, recognizing the operational risk of delay and prioritizing security readiness.
	- VarProcedure was deployed and worked as intended because the change board reached consensus with the security team, overcoming initial concerns through clear communication, risk mitigation, and alignment on shared goals.
	- VarProcedure was executed with zero disruption because prior concerns around impact were addressed through detailed scoping sessions. A technical demonstration clarified the tool’s function, and scans were scheduled to avoid critical production windows.
	- VarProcedure operated effectively because the user/team/manager had built trust with the security team, understood the boundaries of authority, and granted the necessary rights and permissions. This collaboration enabled timely investigation without escalation.
	- VarProcedure was applied across all devices, including executive/VIP endpoints, because leadership acknowledged the importance of consistent controls. Security policies were upheld with support from HR and the CISO, ensuring no exemptions undermined detection capability.
	- VarProcedure worked as expected because clear ownership and maintenance responsibilities for the tool were defined early. This avoided delays and enabled the team to deploy configurations that captured artifacts and indicators tied to the adversary's path.

- Personnel (availability, skill and experience level, motivation, teamwork, quantity)
	- VarProcedure worked successfully because multiple personnel were cross-trained, ensuring continuity even when one expert was unavailable.
	- VarProcedure worked successfully because agents were thoroughly tested, validated, and monitored, ensuring they remained installed and functional across critical systems.
	- VarProcedure worked successfully because the contractor’s hours were managed proactively, and internal staff were trained to continue deployment seamlessly.
	- VarProcedure worked successfully because the approval team established remote processes, enabling decisions even while attending conferences.
	- VarProcedure worked successfully because technicians were strategically distributed, and remote-access capabilities allowed immediate intervention without waiting for physical presence.
	- VarProcedure worked successfully because the SME documented detailed playbooks, and the team was trained to execute them confidently without delays.
	- VarProcedure worked successfully because agents were thoroughly tested, validated, and monitored, ensuring they remained installed and functional across critical systems.
	- VarProcedure worked successfully because new users were onboarded with accelerated training and baseline monitoring tools, allowing anomalies to be detected quickly.
	- VarProcedure worked successfully because engineers received updated training and validation documentation, enabling precise installation and configuration without errors.
	- VarProcedure worked successfully because ongoing cybersecurity awareness training empowered staff to recognize and respond to anomalies immediately.
	- VarProcedure worked successfully because the organization invested in continuous skill development, ensuring personnel expertise remained current with evolving threats.
	- VarProcedure worked successfully because employees were trained to observe behavioral patterns, allowing early detection of insider risks.
	- VarProcedure worked successfully because a strong reporting culture encouraged personnel to escalate suspicious activity without hesitation.
	- VarProcedure worked successfully because cross-functional collaboration ensured that expertise was shared across teams, preventing single points of failure.
	- VarProcedure worked successfully because proactive tabletop exercises prepared personnel to respond effectively under pressure.
	- VarProcedure worked successfully because monitoring dashboards were paired with human oversight, enabling rapid identification of deviations from normal baselines.
	- VarProcedure worked successfully because leadership emphasized preparedness, ensuring documentation, playbooks, and escalation paths were always up to date.

## Procedure Failures
### General Reasons
Technical (Detection Adaptability, Deployment & Infrastructure Readiness, Data Quality & Log Integrity, Visibility & Scope Coverage, and Operational Maturity.)
-  VarProcedure did not detect anything because the attacker changed TTPs (Tactics, Techniques, Procedures).
	- VarProcedure did not detect the attack because the agent/signatures are out of date or were corrupted during a recent update.
	-  VarProcedure did not detect the attack because the agent could not be deployed on the OS/Server/Laptop/Endpoint due to unsupported/legacy/criticality of the asset.
	- VarProcedure did not work because the appliance/server is undergoing patch maintenance and is unavailable.
	- VarProcedure did not work because the data center had an outage or no owner was identified for the system so it was unplugged/ripped out as part of vulnerability management.
	- VarProcedure did not work because agents/logging were installed and configured but alert logic/rule engine/data quality/data completeness was never validated.
	- VarProcedure did not work because only specific/internal/external CIDR rangers were used in the search.
	- VarProcedure did not work because the remote location has intermittent/slow internet service, you must walk a local user through the collection procedures.
	- VarProcedure did not work because logs were not being forwarded to the SIEM and someone has deleted the logs/disabled the service/removed the mountpoint/changed the IP of the syslog server.
	- VarProcedure did not work because procedural documents/network or data flow diagrams were incomplete and did not show a critical path required for the success of VarProcdure.
	- VarProcedure did not work because the agent was recently installed on the device/system and there has not been enough data collected to establish a baseline of normal.
	- VarProcedure did not work because of a lack of required permissions and/or visibility gaps.  An emergency change is being implemented to correct this but it will take time to complete as it requires VP approval.  
	- VarProcedure did not work because the device is not accessible.  Upon further investigation it is discovered that it is actually missing and presumed lost/stolen.	
		 
Financial (Licensing & Coverage Expansion, Procurement & Renewal Timelines, Strategic Investment Alignment, Skills & Talent Investment, Infrastructure & Performance Investment)
- VarProcedure did not work because the budget was not approved to expand licensing for tool/service/project/application to subsidiary/offices/datacenter/branch/new location/work from home/contractors was not approved or was delayed.
	-  VarProcedure did not work because the PO to renew the tool/service got stuck in the payment process. The tool/service stopped before someone noticed.
	- VarProcedure did not work because the tool/service features that would have detected it were part of the more expensive package that was not purchased.
	- VarProcedure did not work because of competing and conflicting projects would have negated/changed where the tool/logging should be implemented.
		-VarProcedure did not work because budget to hire/train a SME on the tool was not approved.  The current team member does not have the required skill/training to do the proper analysis but are doing their best.
	- VarProcedure did not work because the logging level had been lowered due to performance issues/degradations.  Newer devices would have reduced or eliminated the overall impact but had not been approved.  Executives are expediting the expenditure and implementation, to include professional services, to ensure data is available going forward.

Political (Hierarchy & Influence, Ownership & Accountability, Interdepartmental Alignment, and Timing & Prioritization)
- VarProcedure did not work because it was not configured at subsidiary/branch/business unit because Owner/VP/Senior Know-it-All/Project Manager said it would interfere with their CrItIcAl PrOjEcT timeline.
	-  VarProcedure did not work because the project to deploy agent/service/tool/configuration was delayed until next fiscal year by the board.
	- VarProcedure did not work because a member of the change board denied the change to deploy the agent/service/tool based on disagreements with the security team.
		-VarProcedure did not work because prior requests to connect to the network segment/application/tool caused major disruptions in services.  The approver wants a meeting to clearly define what the does and what impact of using the tool could be.  Ever DDoS'ed your network running authenticated vuln-scans on major production implementation days?
	- VarProcedure did not work because user/team/manager feels that the security team already has too much power and refuses to install/apply the required rights and permissions needed.  This will need to be corrected before the investigation can be completed.  This is an important reason to build inter-business relationships to confirm and explain under what circumstances the 'power' would be yielded and who has the authority to approve it.
	- VarProcedure did not work because an executive/VP/VIP stated that rules did not apply to them and therefor worked with HR to require security to remove blocks/tools from their device.  They are being redeployed now and could provide information in the future.
	- VarProcedure did not work because due to disagreements over ownership and maintenance of the tool delayed deployment and configuration that could have shown artifacts related to the attack path used by the adversary.  The team has since been given approval to rapidly deploy the necessary tools/configurations to ensure logging will begin to flow.

Personnel (availability, skill and experience level, motivation, teamwork, quantity)
- VarProcedure did not work because the only person that knows how to do/use VarProcedure is on vacation/retired/RIF/terminated yesterday.
	- VarProcedure did not work because the contractor hired to deploy VarProcedure ran out of hours in their contract.
	- VarProcedure did not work because the team that manages/approves using VarProcedure is away at a conference.
		-VarProcedure did not work because the tool/system requires physical access and the nearest expert technician is hours away.
		-VarProcedure did not work because the SME is out of the country and unable to be contacted.  The team must use the provided playbook and hope for the best, albeit at a much slower pace.
		-VarProcedure did not work because the agents installed on critical systems had been suspected, but not proven, to be the cause of a crash/degradation and had been uninstalled without notifying the security team.  Team/executive conversations/approvals in are progress to have them reinstalled.
		-VarProcedure did not work because the user has recently joined the company and there has not been enough data collected to establish a baseline of normal.
		-VarProcedure did not work because the engineer assigned to perform the installation/upgrade activity was not properly trained in the installation/configuration and missed several key components.   The provided validation documentation was outdated or incomplete and they were unable to confirm the procedure completed successfully or was working as intended.  We have reached out to professional services to make the required changes to ensure the procedure completes successfully in the future.

### Procedure Failures Explanations
- Technical
	- The initial implementation of the SIEM was performed by a 3rd party.  Although agents were installed and data was being collected, the web/application/server/firewall/etc  logs were being sent in chunks and incomplete.
	- Due to the remote location and lack of quality internet,  you must provide the local admin/user with specific walk-through instructions on the evidence collection process and discover there is a version difference (O.S or tool) that does not match with your written procedure’s, therefore, you are encountering unexpected errors conditions.
		-During a planned maintenance activity, the incorrect server was shut-down.  This caused the failover system to become the primary active server, as a result no artifacts were found.  The application team is working on bringing up the correct server and providing access to the IR team.

- Financial 
	-  A member of the application team was a bit overzealous when told they need to trim costs on hardware.  They scripted a cronjob to clean up any webapp logs older than 7 days--you were shipping this to the SIEM, right?
	 - Budget was not approved to allow for maintaining more than 7 days of logs for the authentication data of the web application. 

- Political 
	- The application teams did not create the break-glass accounts as they felt that would be too much power to another team.  The team has been having to work through a single-user who is not as experienced on this system and they keep providing the wrong log, wrong command output, and the delays in getting information are impacting the progress of the investigation.

- Personnel 
	- Due to the remote location and lack of quality internet,  you must provide the local user, who keeps asking a ton of questions as they are not familiar with your team or cybersecurity, with specific walk-through instructions on the evidence collection process. 
	- Our primary forensics led is away at a conference and will not be back for two weeks.  The team is working to find their documentation to obtain artifacts.

## Game Start


## Game Conclusion


## Lessons Learned and Mitigating Controls



References
title
[URL](#)

<h1> Conduct a security audit</h1>

 

<h2>Scenario</h2>
<i>This scenario is based on a fictional company:</i>
<br>

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

My task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist. 
<br />


<h2>Audit scope and goals</h2>

<b>Botium Toys internal IT audit will assess the following:</b>
- Current user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
- Current implemented controls in the following systems: accounting, end point detection, firewalls, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Current procedures and protocols set for the following systems: accounting, end point detection, firewall, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
- Ensure current technology is accounted for. Both hardware and system access.

<b>The goals for Botium Toys’ internal IT audit are:</b>
- To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF) 
- Establish a better process for their systems to ensure they are compliant 
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential management 
- Establish their policies and procedures, which includes their playbooks 
- Ensure they are meeting compliance requirements


<h2>Controls Assessment</h2>

<b>Current assets</b>
<br>
Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.
- Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management
- Internet access
- Internal network
- Vendor access management
- Data center hosting services
- Data retention and storage
- Badge readers
- Legacy system maintenance: end-of-life systems that require human
monitoring


 <table id='simple_table' >
<tr>
	<th> Administrative Controls </th>
</tr>

</table>

 <table id='simple_table' >
<tr>
	<th>Control Name</th>
	<th>Control type and explanation</th>
	<th>Needs to be implemented (X)</th>
	<th>Priority</th>
</tr>

<tr>
	<td>Least Privilege</td>
	<td>Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Disaster recovery plans</td>
	<td>Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Password policies</td>
	<td>Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Access control policies</td>
	<td>Preventative; increase confidentiality and integrity of data</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Account management policies</td>
	<td>Preventative; reduce attack surface and limit overall impact from disgruntled/former employees</td>
	<td>X</td>
	<td>High/Medium</td>
</tr>
<tr>
	<td>Separation of duties</td>
	<td>Preventative; ensure no one has so much access that they can abuse the system for personal gain</td>
	<td>X</td>
	<td>High</td>
</tr>
</table>

 <table id='simple_table' >
<tr>
	<th>Technical Controls</th>
</tr>

 <table id='simple_table' >
<tr>
	<th>Control Name</th>
	<th>Control type and explanation</th>
	<th>Needs to be implemented (X)</th>
	<th>Priority</th>
</tr>

<tr>
	<td>Firewall</td>
	<td>Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network</td>
	<td>NA</td>
	<td>NA</td>
</tr>
<tr>
	<td>Intrusion Detection System (IDS)</td>
	<td>Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Encryption</td>
	<td>Deterrent; makes confidential information/data more secure (e.g., website payment transactions)</td>
	<td>X</td>
	<td>High/Medium</td>
</tr>
<tr>
	<td>Backups</td>
	<td>Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Password management system</td>
	<td>Corrective; password recovery, reset, lock out notifications</td>
	<td>X</td>
	<td>High/Medium</td>
</tr>
<tr>
	<td>Antivirus (AV) software</td>
	<td>Corrective; detect and quarantine known threats</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Manual monitoring, maintenance, and intervention</td>
	<td>Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities</td>
	<td>X</td>
	<td>High</td>
</tr>
</table>

<center>
 <table id='simple_table' >
<tr>
	<th> Physical Controls </th>
</tr>

</table>
</center>

 <table id='simple_table' >
<tr>
	<th>Control Name</th>
	<th>Control type and explanation</th>
	<th>Needs to be implemented (X)</th>
	<th>Priority</th>
</tr>

<tr>
	<td>Time-controlled safe</td>
	<td>Time-controlled safe</td>
	<td>X</td>
	<td>Medium/Low</td>
</tr>
<tr>
	<td>Adequate lighting</td>
	<td>Deterrent; limit “hiding” places to deter threats</td>
	<td>X</td>
	<td>Medium/ Low</td>
</tr>
<tr>
	<td>Closed-circuit television (CCTV) surveillance</td>
	<td>Preventative/detective; can reduce risk of certain events; can be used after event for investigation</td>
	<td>X</td>
	<td>High/Medium</td>
</tr>
<tr>
	<td>Locking cabinets (for network gear) </td>
	<td>Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear</td>
	<td>X</td>
	<td>Medium</td>
</tr>
<tr>
	<td>Signage indicating alarm service provider</td>
	<td>Deterrent; makes the likelihood of a successful attack seem low</td>
	<td>X</td>
	<td>Low</td>
</tr>
<tr>
	<td>Locks</td>
	<td>Preventative; physical and digital assets are more secure</td>
	<td>X</td>
	<td>High</td>
</tr>
<tr>
	<td>Fire detection and prevention (fire alarm, sprinkler system, etc.)</td>
	<td>Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.</td>
	<td>X</td>
	<td>Medium/Low</td>
</tr>
</table>


<h2>Complicance</h2>

<b>General Data Protection Regulation (GDPR)</b>
GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.

-<b>Explanation:</b>Botium Toys needs to adhere to GDPR because they conduct business and collect personal information from people worldwide, including the E.U.

<b>Payment Card Industry Data Security Standard (PCI DSS)</b>
PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

-<b>Explanation:</b> Botium Toys needs to adhere to PCI DSS because they store, accept, process, and transmit credit card information in person and online.

<b>System and Organizations Controls (SOC type 1, SOC type 2)</b>
The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

-<b>Explanation:</b> Botium Toys needs to establish and enforce appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.

<h2>Stakeholder memorandum</h2>

TO: IT Manager, stakeholders

FROM: (Your Name)

DATE: (Today’s Date)

SUBJECT: Internal IT audit findings and recommendations
 
Dear Colleagues,
 
Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.
 
 
<b>Scope:</b>

● The following systems are in scope: accounting, end point detection, firewalls, intrusion detection system, SIEM tool. The systems will be evaluated for:

- Current user permissions

- Current implemented controls

- Current procedures and protocols

- Ensure current user permissions, controls, procedures, and protocols in place align with PCI DSS and GDPR compliance requirements.

- Ensure current technology is accounted for both hardware and system access.
 
 
<b>Goals:</b>

- Adhere to the NIST CSF.

- Establish a better process for their systems to ensure they are compliant.

- Fortify system controls.

- Adapt to the concept of least permissions when it comes to user credential management.

- Establish their policies and procedures, which includes their playbooks.

- Ensure they are meeting compliance requirements.
 
<b>Critical findings (must be addressed immediately):</b>

● Multiple controls need to be developed and implemented to meet the audit goals, including:

- Control of Least Privilege and Separation of Duties

- Disaster recovery plans

- Password, access control, and account management policies, including the implementation of a password management system

- Encryption (for secure website transactions)

- IDS

- Backups

- AV software

- CCTV

- Locks

- Manual monitoring, maintenance, and intervention for legacy systems

- Fire detection and prevention systems

- Policies need to be developed and implemented to meet PCI DSS and GDPR compliance requirements.

- Policies need to be developed and implemented to align to SOC1 and SOC2 guidance related to user access policies and overall data safety.
 
<b>Findings (should be addressed, but no immediate need):</b>

● The following controls should be implemented when possible:

- Time-controlled safe

- Adequate lighting

- Locking cabinets

- Signage indicating alarm service provider
 
<b>Summary/Recommendations:</b> 

It is recommended that critical findings relating to compliance with PCI DSS and GDPR be promptly addressed since Botium Toys accepts online payments from customers worldwide, including the E.U. Additionally, since one of the goals of the audit is to adapt to the concept of least permissions, SOC1 and SOC2 guidance related to user access policies and overall data safety should be used to develop appropriate policies and procedures. Having disaster recovery plans and backups is also critical because they support business continuity in the event of an incident. Integrating an IDS and AV software into the current systems will support our ability to identify and mitigate potential risks, and could help with intrusion detection, since existing legacy systems require manual monitoring and intervention. To further secure assets housed at Botium Toys’ single physical location, locks and CCTV should be used to secure physical assets (including equipment) and to monitor and investigate potential threats. While not necessary immediately, using encryption and having a time-controlled safe, adequate lighting, locking cabinets, fire detection and prevention systems, and signage indicating alarm service provider will further improve Botium Toys’ security posture.

<h1>What is Active Directory?</h1>
Think of Active Directory like a telephone book - but one that stores names, usernames and passwords - along with information on who or what can log onto a system.
Active Directory is used by 95% of Fortune 500 companies.

<h1>Physical Components of Active Directory:</h1>
	<h2>Domain Controller</h2>
		<p></p>Server - physical, virtual and/or in the Azure cloud)</p>
		<p>Hosts Active Directory database</p>
		<p>Responds to authentication requests</p>
		<p>Processes logins and enforces policies</p>
	<h2>Active Directory Database (NTDS.dit)</H2>
		<p>Stores the data for the directory</p>
		<p>Stores log files</p>
		<p>Structure of the database is called a <b>Schema</b></p>
<H2>Domains</H2>
	<p>One of the top level containers in Active Directory</p>
	<p>Holds a collection of objects - users, PCs, groups, etc.</p>
	<p>Serves as an administrative boundary for managing objects inside of it</p>
	<p>Can enforce security & policy settings across all objects inside the domain</p>
<H2>Organizational Units (OU)</H2>
	<p>A container object inside of domains</p>
	<p>Used to group other objects together</p>
	<p>Lowest level container that can allow administrative privileges, group policies</p>
	<p>Orgs frequently split up departments into OUs - Sales, IT, HR, Engineering, etc.</p>
<H2>Non-Container Objects</H2>
	<p>Users</p>
	<p>Computers</p>
	<p>Groups (used for setting access)</p>
	<p>Printers</p>
	<p>Group Policy Objects (GPO)</p>


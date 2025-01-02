<h1>What is Active Directory?</h1>
Think of Active Directory like a telephone book - but one that stores names, usernames and passwords - along with information on who or what can log onto a system.
Active Directory is used by 95% of Fortune 500 companies.

<h1>Physical Components of Active Directory</h1>
	<h2>Domain Controller</h2>
		<p></p>Server - physical, virtual and/or in the Azure cloud)</p>
		<p>Hosts AD Database</p>
		<p>Responds to authentication requests</p>
		<p>Processes logins and enforces policies</p>
	AD Database (NTDS.dit)
		Stores the data for the directory
		Stores log files\
		Structure of the DB is called a Schema
Domains
	One of the top level containers in AD
	Holds a collection of objects - users, PCs, groups, etc
	Serves as an administrative boundary for for managing objects inside it
	Can enforce security & policy settings across all objects inside the domain
Organizational Units (OU)
	A container object inside of domains
	Used to group other objects together
	Lowest level container that can allow administrative privileges, group policies
	Orgs frequently split up departments into OUs - Sales, IT, HR, Engineering, etc)
Non-Container Objects
	Users
	Computers
	Groups (used for setting access)
	Printers
	Group Policy Objects (GPO)


This repo outlines key elements of <b>Windows Local and Domain Accounts</b>.<br/>
	<h2>Local Account</h2> 
 		One user on one PC, with one username and one password</h2>
	<h2>Domain Account</h2> 
 		Allows many users to log onto a PC by using a Domain Controller (server) to store all of the many different Users and their Usernames and Passwords</h2>
	<h2>Domain Controller Directory</h2> 
 		Acts like a phone book to record all of the different Users and their Permissions, along with their Usernames and Passwords</h2>
	<h2>Administering Local User Accounts</h2>	
 		This link is a very helpful resource for implementing and maintaining Local User Accounts</h2>
   		<p>https://learn.microsoft.com/en-us/windows/security/identity-protection/access-control/local-accounts</p>
	<h2>Administering Local User Accounts</h2>
		<p>Click on <b>Start</b> (blue box at bottom left of task bar on Windows 11)</p>
		<p>Type “<b>control panel</b>” in <b>Search Box</b></p>
		<p>Click on <b>Control Panel</b> -> <b>User Accounts</b></p>
		<p>Then make user account changes you want</p>
    	<b><p>OR</b></p>
		<p>Click on <b>Start</b> (blue box at bottom left of task bar on Windows 11)</p>
		<p>Type “<b>run</b>” in <b>Search Box</b> and click on <b>Run</b></p>
		<p>Click “<b>Ok</b>” when “lusrmgr.msc” pop-up box appears and make account setting changes</p>

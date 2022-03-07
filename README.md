# Interview_Questions

```

1.	Service Now Introduction & Overview :  History, Versions, Benefits
2.	Self-service: Basic View of service now and instance creation.
3.	User Administration – User creation. User groups roles Security level, concept of impersonating, System Properties, ACL & Home page creation.
4.	Basic ITIL Concepts. Lifecycle explanation of Incident, change, task, knowledge and problem management.
5.	Tables & Columns, Applications & Menus.
6.	Client side and server side scripting. 
7.	Client script, UI Policies, UI Actions,  Business Rules, Script includes,  
8.	Concept of Gliderecord  and other API’s (G_form, G_user, GlideAJAX, Glidesystem..etc
9.	Service Catalog and its concepts. (record producer, order guide, catalog items)
10.	Workflows and its activities.
11.	SLM, SLA,OLA
12.	Scheduled jobs , Email Notifications, 
13.	Data Policies.
14.	Data Sources & Import set  Transform Maps ,
15.	Integration (SOAP & REST), LDAP, ODBC.
16.	Update sets
17.	Export sets

Snow introduction, versions, Users, groups, roles, delegates, impersonate.
1.	What is service now and benefits? 
2.	Comparison of service now with other ITSM tools.
3.	Give one real example of table relationship. 
Parent child relationship && relationship between table
4.	What is SaaS, PaaS and IaaS. And relate service now with these terminologies.
5.	Servienow versions, which version you are currently working on (have to say Quebec)
6.	What are the advantages of latest version of servienow.
7.	What is your roles and responsibility are as part of service now professional?
8.	What are Roles and Important  of Roles.
9.	How to restrict application or module for specific people.				
10.	Delegates and purpose.
11.	Use of impersonate. how to impersonate and what are the roles required to impersonate.
12.	What is view and how to create a view or restrict a view to set of people.

Tables and relations ships & application/modules creation.
13.	What is reference qualifier? Types and explain
14.	How call a script include from reference qualifier.Advanced – reference equal: javascript:new u_backfillAssignmentGroup(); (script include name.funtion name)
15.	What is dynamic filter options – to call a business rule or script include
16.	Ways to create a table.
17.	What is the limitation of extend table? (10000)
18.	Why, created application is not showing in left menu bar after creating a new application. (Until we have a module created, the application will not show in left or it is restricted with roles.)
19.	Difference between application and module.
20.	What is table schema map?
21.	Encoded query.
22.	What is scoped application and difference between scoped app and global application. (to isolate an application and its configuration from servicneow oob database and configuration, we make scoped application then global scope.)
23.	How to use logging in scoped application.
24.	When we extend a table, what are all the configurations will apply to child table and how to restrict them?

ACL
25.	What is ACL and uses?
26.	Types of ACL’s.
27.	Why cannot a normal user create a new ACL or Edit a ACL. (security_admin)
28.	What roles required to get ACL access and how to get the roles. (security_admin). 
29.	What is admin override (why admin is not able to edit a record or do some activity)
30.	ACL checking activities ( roles, condition and scripts)
31.	Difference between –None-. *, table.active (incident.caller).
32.	What is the execution order of checking in ACL. (field and then table)
ACL allow – incident.active & ACL – deny – incident.* (will active field get access?)
true – false -true

33.	What happened if there are multiple ACL that provide access true and false.(one should be satisfy)
34.	Give an example for script based ACL.
 UI Policy, System Properties, Home page
35.	What are system properties and explain with few examples?
36.	While exporting data into excel/CSV, I am unable to get data more than 1000 records, what is the problem and how to solve it.
37.	What is UI policy.
38.	What are the main actions can be done via UI Policy.
39.	What is script option in UI policy. Explain with examples.
40.	What is the difference between UI policy action and UI policy.
41.	What is “reverse if false”, Global, On Load, inherit UI policy page
42.	What is home page and how to create a home page.

ITIL, SLA:
43.	SLA definitions and types and description of each type. Why SLA is required.
44.	SLA snow page options
45.	Difference between response SLA and resolution SLA.
46.	What is SLM.
47.	What is incident and life cycle of incident. 
48.	What is problem and types of problem? When problem with be raised.
49.	Real time problem situation and explain the entire process.
50.	What is change, types and lifecycle?
51.	What is task and lifecycle.
52.	Retroactive start and pause.
53.	Difference between incident and Risk.

Client scripts 

54.	What is client scripts and explain it types with examples. 
55.	Service now architecture (form layer / script layer /database layer)
56.	What is the oncelledit type and what are the limitations of it.
57.	What are supportive API’s for client script.
58.	What are the limitations of client scripts.
59.	What is the difference between client script and UI policy
60.	Where are the places client script will be useful.
61.	Explain few client API’s with examples
62.	Order of execution (ACL, client scripts, BR, ui policy, dictionary…).
63.	What is dictionary?
64.	What is dictionary override. Explain with some example.
65.	Base table and child table relationships.
66.	2 level , 3 level traversing and DOTWALKING
67.	Difference between glideRecord vs getreference or getreference vs get value?
68.	Difference between UI policy and client script.
69.	What is the difference between Global vs scoped client script. Which one is suggested approach?
70.	Retroactive start and pause in SLA
71.	Client script best practices (avoid global CS, use scratchpad to limit server calls, don’t use gliderecord, best us of script include, don’t use DOM, plan asyn calls, getreference or ajax, use UI policies)

Update sets
72.	What is update set and respective table .  where the updates will capture(sys_update_set.xml). state values. (sys_update_set and sys_update_xml)
73.	Limitations of update sets
74.	Update set best practices.
75.	Ways to move update set from one env to another. Which one is good to follow?
76.	What is update source and how to configure?
77.	Preview issues , backout
78.	What is merged update sets
79.	
Reports
80.	What is reports
81.	How to create a report, a new report or report from data source.
82.	How to create a report data source
83.	Share, export, publish, schedule options and use cases.
84.	What is database views with example.
Scheduled Jobs, UI action, Form design and Form layout:
85.	Scheduled jobs and what are the things we can schedule.
86.	What is template and how to create a template for incident or change (toddle bar)
87.	Scheduled import clean up – how to do (for 7days once)
88.	What is UI action and purpose of the UI action in real time examples (change example)
89.	UI actions and placements.
90.	What is form design and form layout?
91.	What is use of slush bucket?
92.	Difference between sys_user.list and sys_user.LIST and sys_user.FORM and Sys_user.form
93.	What is stats for?

Import set, update source and Transform maps
94.	Explain import set table and transform maps with one example.
95.	How to import data from a table
96.	How to export data from a table
97.	What are the limitations of direct export and import?
98.	What is mapping fields, what is the difference between manual mapping (explicit mappaing) and auto mapping.
99.	What is data source?
100.	Types of data source and port values for each type.
101.	Explain Coalesce.
102.	Use of transform maps scripts with real time example.
103.	Types of transform maps
104.	What are when options and explain all the options(onstart….) and difference between each types
105.	Form options of transform maps like "Run business rules, Enforce mandatory fields, copy empty fields.
106.	Execution flow of transform script types. (start,before,after,complete) SBAC

Business Rules, data policies, Email Notifications, Inbound Email Actions.

107.	What is business rules and types , explain with real time scenarios.
108.	What are the main objects on after and async
109.	What is scratchpad and where are the places, g_scratchpad will be useful.
110.	what is data policies and actions can be done via data policy
111.	what is the diff between data policy and Ui policy (datapolicy – time of data import and webservices).
112.	How to convert data policy to ui policy and ui policy to data policies and what the conditions to be met. (Global-checked , run script – cleared, visible – leave alone)
113.	when data policy will be used
114.	What is email notifications
115.	what is inbound email action. explain with example
116.	what is email digest.
117.	What is the use of weight option in email notification.
118.	How an email will be recognized by service now system( watermark, subject – prefix, reply & from /table)
119.	how the data will be read from email (email.body, email.subject) with examples
120.	Inbound email action in details, event management.
121.	What is the format and flow of an event?
122.	What is the use of param1 and param2 ${event.param1}
123.	How to schedule a event from script (gs.eventQueueScheduled().
124.	What is the syntax to run an event (eventqueue)
125.	How to create a link to approve/reject an approval In email? ${mailto:mailto.rejection} //rejection is an email template 
126.	How to print test or something from email script : template.print(“Summary of “);
127.	Explain inbound email action with some examples
128.	What is email script
129.	What is the use of email template and how to trigger a template from script.
130.	what are the disadvantages of business rules
131.	what are the advantages of business rule
132.	explain all the types of business rules with examples
133.	Gliderecord methods with examples 
134.	Addquery, addorcondition, next, hasnext, _next, addjoinquery, addnullquery, addactivequery.
135.	What is gliderecord – set workflow method.
136.	What is the diff between g_form, g_user,gs and gliderecord.
137.	What is the difference between g_user.hasRole vs g_user.hasRoles vs g_user.hasRoleExactly vs g_user.hasRolefromLists. (hasrole is role +admin & hasroleexactly (only role)
138.	What is the use of gs.info and gs.log

Service Catalog & workflow
139.	What is service catalog and types – describe with real time examples
140.	What is the variable and variable set?
141.	What is category?
142.	Why my catalog item is not showing in service catalog.
143.	What is 3 step process
144.	What is rule base
145.	What is order guide
146.	Difference between order guide to catalog.
147.	What is the difference between record producers to catalog?
148.	What is cascading variables?
149.	How read variable values from record producer form (producer.variablename)
150.	How to read variable values from catalog form In script or workflow script (current.varaible.pool.variablename or current.variables.variablename)
151.	How to start/stop a workflow from script
152.	Explain few important variable types.
153.	How to limit service catalog request form to certain group or people.
154.	What is the user criteria?


Workflow questions:
155.	What is the difference between workflow and execution plan
156.	What are the basic activities available in every workflow? Begin and End
157.	Workflow activities for notifications with example (approval user, group, action and rollback, approval cordinator)
158.	Workflow activities for conditions (if, switch and wait for condition)
159.	Workflow activities for notifications.
160.	What are the ways to select recipients of the notifications (manual, script, dynamic)
161.	What is subflow and explain with examples
162.	How to pass values between activities
163.	How to pass values from main workflow to subflow.
164.	What is the difference between catalog task to task- activities to be create them
165.	What is timer activity
166.	What are utilities activities. Explain with examples 
167.	Branch , Join, lock / unlock, return value, set value, turnstile & runscript.

Script includes

168.	What is script include and uses. Explain with example
169.	What is the difference between script include and business rule
170.	What is class and functions.
171.	How to call a script include from client script and business rule.
172.	What is callback function
173.	What is the difference between getXML and getXMLwait.
174.	What is client callable option in script include
175.	Types of script include and use cases of script include (where are the places we use script include)
176.	How to call a script include from another script include. (gs.include())
177.	Difference between gs.include() and NewInclude() – A:gs.include is to call a script include and include() is to initialize a script include into a object.

178.	Where are the places “scripts” can be used.
179.	What is GlideAJAX, Getparameter, addparameters in script include concept.
180.	When we call a service side script from client side, in which format, the data will transfer?  XML.
181.	Where are the places , script includes can be used
182.	What is the difference between script include and global business rule
183.	Which kind of script can be used in script include
184.	What are the best practices of scripting.
185.	What is global business rules and best practices.
186.	What is backround scripts and real time example
187.	What is the difference between background script and scheduled job. Which account the job will run when we execute
188.	How to schedule a script , explain with example

Integration:

189.	What is integration and explain with real time example.
190.	What are the types of web services
191.	What is the pre-reqs required to set integration between for two databases, from user and table level. That roles are required for web services activities
192.	Difference between import and integration
193.	What is the difference between REST and SOAP,
194.	Types of webservices
195.	What are the pre-reqs needed to set a communication(integration) between two sources.
196.	Explain with real time scenario
197.	What are advantages and disadvantages of SOAP.
198.	What are the methods of REST
199.	What are the methods of SOAP
200.	What are scripted webservice and what is response and request.
201.	What is default source type of rest and soap.
202.	What are the roles required for webservices.
203.	sn_ws.RESTMessageV2 and sn_ws.SOAPMessageV2
204.	what are the tools you use to test the integration part before going to actual work. Soap UI 4.3, advanced rest client -chrome addin .postman – tool.
205.	Default supportive format of REST.
206.	What is an API and how to analyses an API.
Attachments
207.	How to hide attachments for a group or location (disableattavhment())

General questions:
208.	What s single tenant & multi tenant (domain separation – MSP – manager service provider).
209.	What is the difference between GlideForm to g_form (GlideForm is an API or class with many methods where g_form is a object to call the API methods.)
210.	CMDB – top down & Bottom up approaches.
211.	Explain scripting layers in service now.
212.	If we create a onload client script and before business rule on load, which one will run first. And why
213.	Update set move to other instance , best practice.
214.	What happens if we use g_form in business rule.
215.	Will current can be used in after business rule? If no , what is the alternative.
216.	Sprint release story ?
217.	How to make the authentication in Scripted rest API (using ACL)
218.	How to restrict/Allow few table accesses for a group of people (ACL – System Properties)
219.	Best Practices of client Script and Business Rules.
220.	Field Mandatory – how to do ? If UI policy- how can u handle in list view?
221.	Scenario of Tech parks - 5 buildings - parking floors (2) - parking slots (few number) > Design
222.	Madrid enhancements.
223.	Limitation of current.update() and alternative for this.? Setworkflow(false)
224.	Sc# - workflow manager approval, if manager don’t approve in 5 days, the approval should go to Manager’s manager.
225.	SC# - Order guide, if two catalog first level approvals have a same person as approver, cascade approvals to other catalog approvals.
226.	What is the different methodology of agile? (scrum , XP & Kanban).
227.	Fix Script vs backround script
228.	Ui macro scenario #jelly script
229.	GlideDialogWindow scenario. 


Others
-- How to upgrade service now instance - RAISE A HI TICKET IN SERVICENOW
-- ZING SEARCH technique is used in service now to search for words.
-- What kind of protocol does servicenow use to send and recieve email notifications(Configure in Email Accout module)
   POP3-- To send emails from servicenow to outside
   SMTP-- To recieve emails from outside to servicenow

Banner logo may not defined in My Company or showing Servicenow Logo

   Resolution
   Please follow the steps below:

   Login as an administrator using UI16.
   Go to My Company under the System Properties application module.
   Add the field 'UI16 Banner Image' to the form layout if not already present on the form.
   Upload the company image from the Image Library.
   Save and update the record.
   Refresh the browser.



```


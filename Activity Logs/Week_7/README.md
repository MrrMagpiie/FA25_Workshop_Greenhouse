# Activity Log
- Created an application through the App Engine Studio(AES) that includes some rudimentary tables to fill out the Data structures defined in the design documents on the Github.
- Created admin users for everyone to be able to access the ServiceNow Instance.
- Had a meeting with Prof Stockman about direction for the Greenhouse management software project.
	- Went over high level requirements for the software again so everyone is on the same page
	- Redefined roles and responsibilities for everyone 
		- Isaac: Frontend development
		- Zach: Database development 
		- Marquan: Database development and Story management
		- Marquise: Story management
		- Taran: PM/ Whatever needs doing and Hardware Integration
		- Cody: Hardware Integration
	- We had some issues with assigning Stories within the ServiceNow instance. This issue has been resolved but not tested
	- We had some issues with the admin profiles that we set up but it has been resolved and everyone has access to their admin profiles now
	- Showed everyone the App within AES and confirmed that everyone has access to it.  
- Identified Possible API's [This](https://docs.servicenow.com/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html) we can use to integrate with ServiceNow
- The hardware has been ordered for the greenhouse project. 
- Discussed with Prof. Brett the specifics of integration for the hardware. 
	- Decided to use ESP home(ESP) and Home assistant(HA) as the hardware hub for the project. the Combination of ESP and HA will collect the data and control the hardware then we will use the previously mentioned API's to connect HA to the ServiceNow application. This should allow us to continue with our current development course without adding any new complications or responsibilities to the Web Dev team and should simplify the coding for the Computer Workshop team. 


# Current Goals:

## Get Stories Working 
Create Stories within Service now to give everyone a bit more direction as to what needs to be done

## First Steps of Integration
Now that we have a specific parts list we can find the tools within ESP for the hardware that has been ordered.

## Populate Database
We have some rudimentary tables set up in the Data section of the App we can fill them with some sample data until the hardware integration is up and running 

## Create Working Frontend
Now that we have some rudimentary tables set up we can reference to them and start working on a Working front end in the Experience section of the APP 

## Foster Better Team Communication
- I am going to do a log like this every week to keep everyone apprised of what's happening and post it in the Teams chat 
- I am going to add a place on the Github repo to store these logs

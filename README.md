# SAP BTP Extention Suite & Integration Suite Bootcamp 2021

Exercises made by:

`Fullname` | Jose Reynaldo Bautista Palomino
`Email` | <jrbautista@indracompany.com>
`Company` | Indra Peru

## Day 1 - 12 Factor App

### Requirements for the badge
A screen capture of the application running for a specific route where we can see:
-	A URL randomly generated and different from the one below (12-dogs.cfapps….)
-	The Configurations DOG_BREED and DOG_SUBBREED set
-	A collection of dogs populated 
    - It shows the DB is created and binded to the app
-	A CF_INSTACE_INDEX > 1
    - Shows the app is scaled out

![12-dogs app running](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%201%20-%20Cloud%20Native/Day%201%20-%20Cloud%20Native%20-%2001%20-%2012-dogs%20app%20running.png)

## Day 2 - CAP
### Requirements for the badge
For the Cloud Application Programming topic, to verify completion of assignments, we would need to make sure of the following:
**Success Deployment of the Bookshop solution on their own BTP (trial) account.**
1. **Relevant Services & Instances** created under Cockpit > Services & Instances.
2. Service application under Cockpit > Cloud Foundry > Dev > Applications > **bookshop-srv**. 
3. **UI on Launchpad** under HTML5 Applications & Working App (with SAP HANA Cloud enabled).
**Screenshots Proof as follows:**

**1. Relevant Services & Instances created under Cockpit > Services & Instances.**

*bookshop-db, bookshop-destination-service, bookshop-html-app-host-service, bookshop-xsuaa-service*

![Instances and services](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20CAP/Day%202%20-%20CAP%20-%2001-%20Instances%20and%20services.png)

**2. Service application under Cockpit > Cloud Foundry > Dev > Applications > bookshop-srv.**

*bookshop-srv*

![Check apps on BTP](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20CAP/Day%202%20-%20CAP%20-%2002%20-%20Check%20apps%20on%20BTP.png)

**An application route should be created for the app to access into the bookshop service.**

![App Route on BTP](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20CAP/Day%202%20-%20CAP%20-%2003%20-%20App%20Route%20on%20BTP.png)

**Working app of bookshop-srv.**

![App service on BTP](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20CAP/Day%202%20-%20CAP%20-%2004%20-%20App%20service%20on%20BTP.png)

**3. UI on Launchpad under HTML5 Applications & Working App (with SAP HANA Cloud enabled).**

![Book Catalog Tile on Launchpad](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20CAP/Day%202%20-%20CAP%20-%2005%20-%20Book%20Catalog%20Tile%20on%20Launchpad.png)
![Book Catalog App on Launchpad](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20CAP/Day%202%20-%20CAP%20-%2006%20-%20Book%20Catalog%20App%20on%20Launchpad.png)

## Day 2 - SaaS Multitenant
### Requirements for the badge
A screen capture of the application running for a specific consumer route where we can see:
- The "/catalog/Sales" page
- The full path must be visible so we can check 
    - The subaccount name of the specific tenant/consumer 
        - Should be different for each participant, in my case it is "059820e6trialc1"
    - the CF space 
        - In my case "dev", many participants might use the same space name
    - The application name
        - In my case "captrmsaas", many participants might use the same app name 
    - The path will end with "/catalog/Sales" for all participants 
- We can see some data values
    - Values will be similar for many participants as the DB is initialized with some default values

![Check Sales Service for Consumer 2](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%202%20-%20SaaS%20Multitenant/Day%202%20-%20Saas%20Multitenant%20-%2001%20-%20Check%20Sales%20Service%20for%20Consumer%202.png)

## Day 3 - Integration Suite
SAP Integration Suite Badge will be granted for attending Session 1 and 3 and
submitting hands-on proof for Session 3

Requirements for the badge: 3 Screenshots proof for the below three requirements and
"Get Sale Order" log file as an attachment.

**1. Requirement 1/3: The integration package**

This step will create the integration package where the integration flow will be stored
and develop the integration flow.

![Deployed IFlow](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%203%20-%20Integration/Day%203%20-%20Integration%20-%2001%20Deployed%20IFlow.png)

**2. Requirement 2/3: Message Processing Log.**

The first row of tiles is for the individual executions of the integration flow. Click on the
first tile to see all executions of all integration flows, change the time filter to see "All".

![Executions on Monitor](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%203%20-%20Integration/Day%203%20-%20Integration%20-%2002%20Executions%20on%20Monitor.png)

["Get Sales Order" log file](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%203%20-%20Integration/Day%203%20-%20Integration%20-%20MessageLog-Commission_Flow-attachment_2-2_%20Get%20Sales%20Order.txt)

**3. Requirement 3/3: SAP Event Mesh Webhook**

The first row of tiles is for the individual executions of the integration flow. Click on the
first tile to see all executions of all integration flows, change the time filter to see "All".

![WebHook Detail](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%203%20-%20Integration/Day%203%20-%20Integration%20-%2003%20WebHook%20Detail.png)

## Day 4 - SF Onboarding
### Requirements for badge:

Capture the following two screenshots to show proof of completion. 

1. The bas system workflow with the completed workflow build for the India onboarding
2. Capture of the Workflow management with two instances started. One for USA and one for IND


![Workflow India](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%204%20-%20Workflow/Day%204%20-%20Workflow%20-%2001%20Workflow%20India.png)
![Instance for India](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%204%20-%20Workflow/Day%204%20-%20Workflow%20-%2002%20Instance%20for%20India.png)
![Instance for USA](https://raw.githubusercontent.com/jrbpraven/bootcamp2021/main/img/Day%204%20-%20Workflow/Day%204%20-%20Workflow%20-%2003%20Instance%20for%20USA.png)

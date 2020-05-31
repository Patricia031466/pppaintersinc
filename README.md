# pppaintersinc
 Control of Proposal PPainters Inc

 What is it
Website that allows users to issue a proposal that will then be approved by the manager and sent by email to the Client. This proposal is based on various services related to the maintenance of buildings in the area of painting. It will allow a better control of clients and service providers through what is budgeted over time through the use of certain filters and preferences.

 Technical Summary
 Python
 SQLite
 Entity Framework for Database
 ASP.NET MVC for front end
 Bootstrap for UI
 How to make project work
 Open Repository on browser [link to project]
 Open Project in Visual Studio by going to "Clone or download" > "Open to Visual Studio"
 Go to ppaintersincShared > Data > API > APIKeysTemplate
 Rename "APIKeysTemplate" class to "APIKeys"
 Request keys from me or generate your own (AttomKey -> https://api.developer.attomdata.com/signup & PpaintersKey -> https://www.zillow.com/howto/api/APIOverview.htm)
 Add given AttomKey & PpaintersKey to APIKey class add-api-keys
 Press F5 to run project
 Open localhost page
 Type projectcode to search for project in the currently year
 Features
 Current proposal data
 
 Proposal Details
 Project associate
 Resume by Client
 Proposal History
 Persist data in database
 Calculators
 
 Property Rental
 Calculate Subtotal by entry (Amount times Price)
 Calculate Retention  (10% Total)
 Calculate Total (Add Subtotal)
 Reports
 Page to view reportPPainters
 Pdf report of the proposal ==
 Page to see proposal ++ by Zip
 
 Ability to filter between deals
 Ability to add a proposals ++
 Milestone List
 Fetch data from Proposal API (Week 4)
 
 Create database to persist proposal details. (Week 5)
 
 MLS Number
 Zip Code
 Contractors Needed
 Repairs Needed
 Create calculators to find best zip for service (Week 6)
 
 Create page to view proposal (Week 7)


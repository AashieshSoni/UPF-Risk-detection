# UPF-Risk-detection
Unified Payment formatter for Fraud Detection AND AML compliance

Advance AI Agentic Data Analytics Solution for BFSI  
Admin Menu Components
a. Access Management 
	User management - add, update, inactive, active (MFA,SSO)
	Roles wise -permission -yes/No
                       Investigator, Analyst, Team Lead, Manager, Supervisior, System Admin, GA(internal desk),Auditor
        feature wise permission -yes/No
	               Alert,Cases,SAR Filing,Watchlist,OFAC Sanctioned,Screening,KYC,CTR, Export, Filter Audit
b. Policy Management
	Standard Policy
		TM rules -21 different type , conditions in each rule
		CTR rules -2 different type , conditions in each rule
		STR rules , conditions
	Adhoc Policy
		Data Injection Alert API   
		Data Injection Cases API  
c. Entity Management
	Customer ID, AccountID, PhoneID, NetworkAccountlinkID, EmailID, AddressID, transactionID
	Customer Entity inclusion / Exclusion 
	Customer Risk Questions rating
	Customer Creditor Risk Ratio - risk score,-risk type
	Category wise
		Group wise -Customer ID, AccountID,
		Amount Range wise - ProfileID
		Profile wise - Add new ProfileID
	List of Values
		country wise risk level, risk score
		RISK type -High, Medium, Low
		RISK level
		RISK factors - Payment Channels wise -risk type, risk level, risk score
		City wise -risk type,  risk score
		Zipcode wise -risk type,  risk score
 	
		
d. Preventive and Detective process 
	 Customer Due Diligence (CDD) ongoing
         Customer Due Diligence (CDD) onboarding
         Enhanced Due Diligence (EDD)
         OFAC sanctions score
         Watchlist screening score
         Feature KYC
e. View Audit 
	UPF Data injected -validation
	System audit (auto process or scheduler)
	User operation audit	
f. UPF Data injected 
	Data issue -daily,weekly, monthly,queartly
	no of records injected
	no of records warning
	no of records error
	no of records processed
	

Unified payment formatter(UPF)
1. All payment channel data should convert into Unified payment formatter(UPF)
2. All customer master data should be kept fetch into weekly basis or OnDemand when add/change of information
3. All internationalization customer or internationalization payment channel integration should be kept into different database
4. List of customer profile , List of Value for each or every risk level should be define
5. Categarisation of Customer Entity /customer profile based for define risk score, risk factor and risk level - Customer Risk Ratio
6. Customer KYC for bench marking -risk score, risk factor and risk level - Customer Risk Ratio
7. List of Risk factors or type of risk factor for payment channels 
8. Policy Rules and Condition on  Account transaction monitory and Currency Transaction Report, Currency Exchange report, Foreign Transaction Report
9. Additional OFAC Sanctioned , Watchlist(314a) , Screening - on Customer account (kyc),entity or transaction amount based and type of accounts duration
10. Generate Alerts based risk score, risk factor and risk level for point 6 to 10 
11. Alert workflow life cycle -peer review, esclation, manager review, redirect to
12. Case creation from Alert and case workflow life cycle -peer review, escalation, manager review. add multiple alerts to cases
13. SAR filing creation -and SAR workflow life cycle, SAR Narration, transaction attachment, detail investigation attachment, Customer summary
14 Based on point 11 to 13 Alert to cases to SAR Filing or Fintrack filing should fetch customer detail automatically 
16. Filtrations/Searching data in each feature common export to excel, search on each #id, customer name and other fields.
17. Dashboard for individual investigator and lead investigator and manager
18. Ad-hoc or out of box Policy rules condition creation
19 Fraud or AML -> Roles & permission individual investigator and lead investigator and manager
20 login to system  individual investigator and lead investigator and manager
21 Multi factor authentication to system, Single sign on to system, 


#Policy management solutions include:
Centralized Digital Storage: Organizes policies , define new adhoc conditions and Standard conditions as documents in a single repository for easy access.
Automated Workflows: Manages the entire policy lifecycle from creation to approval, and renewal.
Tracking and Alerts: Provides notifications for key events like missing kyc details, Watchlist cyclet, and policy over rules for customer Entity.
Reporting and Compliance: Offers dashboards for tracking audit histories, compliance monitoring, and reporting.
Multi-Platform Access: Often available as web tools or mobile apps for customer portfolio viewing and tracking transaction.




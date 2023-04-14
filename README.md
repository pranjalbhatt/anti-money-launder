# Anti-Money Laundering 

Identify and classify customers with fraudulent behaviour. Identify nefarious activity and content exploitation.

# Dataset 

## Customer Train  (For Supervised Model)

customer_id_mskd:	Masked customer CID,   
jurisdiction_code:	Oracle jurisdiction code (e.g., CA03, CA12, etc.),   
client_type_aml:	Business/Individual,    
industry_code_aml:	SIC code,    
occupation_code_aml:	Enterprise wide occupation code,    
country_of_domicile_aml:	Domicile country code,   
occupation_status_code_aml:	Occupation status code,   
customer_status_aml:	Customer status code (e.g., active, etc.),   
export_ts:	Data processing timestamp,    
rating:	Expert-created label    

## Customer Big 

customer_id_mskd:	Masked customer CID	CID = Customer,   
jurisdiction_code:	Oracle jurisdiction code (e.g., CA03, CA12, etc.),    
client_type_aml:	Business/Individual,   
industry_code_aml:	SIC code,    
occupation_code_aml:	Enterprise wide occupation code,   
country_of_domicile_aml:	Domicile country code,  
occupation_status_code_aml:	Occupation status code,	  
customer_status_aml:	Customer status code (e.g., active, etc.),    
export_ts	Data processing timestamp,   
PCD_CDA	Count of CDA	CDA = Chequing,  
PCD_CMS	Count of CMS	CMS = Cash Management,   
PCD_CRC	Count of CRC	CRC = Credit Cards,   
PCD_LIN	Count of LIN	LIN = Insurance,   
PCD_LLC	Count of LLC	LLC = Loans,   
PCD_MOR	Count of MOR	MOR = Mortgages,    
PCD_MUF	Count of MUF	MUF = Mutual Funds,   
PCD_SAV	Count of SAV	SAV = Savings,    
PCD_SDB	Count of SDB	SDB = Safefty Deposit Boxes,   
PCD_TED	Count of TED	TED = Term Deposits   


## Transaction Data 

customer_id_mskd:	Masked customer CID,   
month:	The month that the summary is for (2019 April 15 to 2020 April 15),   
in_amt:	Total value of incoming assets over one month (CAD),   
in_cnt:	Number of incoming transactions over one month (CAD),   
out_amt:	Total value of outgoing assets over one month (CAD),   
out_cnt:	Number of outgoing transactions over one month (CAD),   
trsactn_type:	Channel over which the transaction takes place (e.g. debit, cash, etc...)

# Methodologies/Evaluation

Use of Neural Network and other present technniques to determine the transaction gravity 
1. Alert
2. Case
3. Reporting

### Strategy & Exploration
* breadth and depth of the work 
* understanding data and models developments in various ways

### Results
* efficacy of communcation (persuasive) 
* coherence of ideas 
* clarity of results



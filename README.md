# Term-Deposits-Conversion
Term deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing, and digital marketing.  Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.  The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y).

1 - age (numeric) 

2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services") 
3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed) 
4 - education (categorical: "unknown","secondary","primary","tertiary") 
5 - default: has credit in default? (binary: "yes","no") 
6 - balance: average yearly balance, in euros (numeric) 
7 - housing: has housing loan? (binary: "yes","no") 
8 - loan: has personal loan? (binary: "yes","no") 
# related with the last contact of the current campaign: 
9 - contact: contact communication type (categorical: "unknown","telephone","cellular") 
10 - day: last contact day of the month (numeric) 
11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec") 
12 - duration: last contact duration, in seconds (numeric) 
# other attributes: 
13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact) 
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted) 
15 - previous: number of contacts performed before this campaign and for this client (numeric) 
16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

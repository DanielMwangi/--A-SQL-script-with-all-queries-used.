# --A-SQL-script-with-all-queries-used.
A SQL script with all queries used.

Connect to the PostgreSQL database using the provided connection string and explore the dataset.
 
1). Write SQL queries to find answers to the following key questions:
 
1- What is the total amount of debt owed by all countries in the dataset?

2823893300259.09
2- How many distinct countries are recorded in the dataset?

124
3- What are the distinct types of debt indicators, and what do they represent?
 
indicator_code	indicator_name
DT.DIS.DLXF.CD	Disbursements on external debt, long-term (DIS, cu
DT.INT.DLXF.CD	Interest payments on external debt, long-term (INT
DT.AMT.BLAT.CD	PPG, bilateral (AMT, current US$)
DT.DIS.BLAT.CD	PPG, bilateral (DIS, current US$)
DT.INT.BLAT.CD	PPG, bilateral (INT, current US$)
DT.AMT.MLAT.CD	PPG, multilateral (AMT, current US$)
DT.DIS.MLAT.CD	 
DT.INT.MLAT.CD	 
DT.AMT.OFFT.CD	 
DT.DIS.OFFT.CD	PPG, official creditors (DIS, current US$)
DT.INT.OFFT.CD	PPG, official creditors (INT, current US$)
 	Principal repayments on external debt, long-term (
 	Interest payments on external debt, long-term (INT
DT.INT.DPNG.CD	 
DT.AMT.BLAT.CD	 
 	PPG, bilateral (DIS, current US$)
DT.AMT.PBND.CD	PPG, bonds (AMT, current US$)
 	PPG, bonds (INT, current US$)
DT.AMT.PCBK.CD	PPG, commercial banks (AMT, current US$)
DT.DIS.PCBK.CD	PPG, commercial banks (DIS, current US$)
DT.INT.PCBK.CD	PPG, commercial banks (INT, current US$)
DT.DIS.MLAT.CD	PPG, multilateral (DIS, current US$)
 	PPG, multilateral (INT, current US$)
DT.AMT.OFFT.CD	PPG, official creditors (AMT, current US$)
 	PPG, other private creditors (AMT, current US$)
DT.DIS.PROP.CD	PPG, other private creditors (DIS, current US$)
DT.INT.PROP.CD	PPG, other private creditors (INT, current US$)
DT.AMT.PRVT.CD	PPG, private creditors (AMT, current US$)
 	PPG, private creditors (DIS, current US$)
DT.INT.PRVT.CD	PPG, private creditors (INT, current US$)
DT.AMT.DLXF.CD	Principal repayments on external debt, long-term (
DT.AMT.DPNG.CD	Principal repayments on external debt, private non
DT.INT.DPNG.CD	Interest payments on external debt, private nongua
DT.INT.PCBK.CD	 
DT.INT.MLAT.CD	PPG, multilateral (INT, current US$)
DT.AMT.PROP.CD	PPG, other private creditors (AMT, current US$)
 	Disbursements on external debt, long-term (DIS, cu
DT.INT.PBND.CD	 
DT.AMT.MLAT.CD	 
DT.AMT.PRVT.CD	 
DT.DIS.PRVT.CD	 
DT.AMT.PBND.CD	 
DT.INT.PBND.CD	PPG, bonds (INT, current US$)
 	PPG, official creditors (AMT, current US$)
DT.INT.DLXF.CD	 
DT.DIS.PRVT.CD	PPG, private creditors (DIS, current US$)
 	PPG, bilateral (AMT, current US$)
DT.DIS.OFFT.CD	 
 	PPG, private creditors (INT, current US$)
 	PPG, commercial banks (INT, current US$)
 	PPG, multilateral (DIS, current US$)
DT.AMT.PCBK.CD	 
 	 
DT.DIS.BLAT.CD	 
 	PPG, multilateral (AMT, current US$)
DT.INT.PROP.CD	 
 	PPG, bilateral (INT, current US$)
 	PPG, commercial banks (AMT, current US$)
DT.INT.PRVT.CD	 
 	PPG, official creditors (INT, current US$)
 	Principal repayments on external debt, private non
 	PPG, private creditors (AMT, current US$)
DT.INT.BLAT.CD	 
 	PPG, commercial banks (DIS, current US$)
DT.INT.OFFT.CD	 
 	PPG, official creditors (DIS, current US$)
DT.AMT.DPNG.CD	 
 	Interest payments on external debt, private nongua
DT.AMT.DLXF.CD	 
DT.AMT.PROP.CD	 
DT.DIS.DLXF.CD	 
 	PPG, bonds (AMT, current US$)
 	PPG, other private creditors (INT, current US$)
DT.DIS.PROP.CD	 

4- Which country has the highest total debt, and how much does it owe?
 
Principal repayments on external debt, long-term (AMT, current US$)	6385102859

5- What is the average debt across different debt indicators?
 
indicator_name	avg_debt
Principal repayments on external debt, long-term (AMT, current US$)	6385102859
Principal repayments on external debt, private nonguaranteed (PNG) (AMT, current US$)	5617528433
Disbursements on external debt, long-term (DIS, current US$)	1952507088
PPG, private creditors (AMT, current US$)	1813818528
(NULL)	1538484010
Interest payments on external debt, long-term (INT, current US$)	1466122951
PPG, bonds (AMT, current US$)	1414863561
PPG, official creditors (DIS, current US$)	1351457479
PPG, official creditors (AMT, current US$)	1274168400
PPG, bilateral (DIS, current US$)	1125436970
PPG, other private creditors (AMT, current US$)	884860453
PPG, multilateral (DIS, current US$)	838769978.3
PPG, bonds (INT, current US$)	834951112.9
PPG, commercial banks (AMT, current US$)	805805039.7
PPG, private creditors (INT, current US$)	744083355.9
Interest payments on external debt, private nonguaranteed (PNG) (INT, current US$)	717492049.1
PPG, bilateral (AMT, current US$)	597027171.4
PPG, multilateral (AMT, current US$)	547859193.9
PPG, official creditors (INT, current US$)	321224581.4
PPG, private creditors (DIS, current US$)	303359591.3
PPG, commercial banks (DIS, current US$)	271701783.1
PPG, commercial banks (INT, current US$)	177040112.1
PPG, bilateral (INT, current US$)	134041574
PPG, multilateral (INT, current US$)	131281504.9
PPG, other private creditors (DIS, current US$)	92727244.6
PPG, other private creditors (INT, current US$)	5691548.574

6- Which country has made the highest amount of principal repayments?

7- What is the most common debt indicator across all countries?

indicator_name	count
\N	250

8- Identify any other key debt trends and summarize your findings.


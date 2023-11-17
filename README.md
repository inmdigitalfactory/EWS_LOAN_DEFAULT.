# EWS_LOAN_DEFAULT.
This is the early warning system set to predict default(Lateness on instalment by 60 days) for customers with existing loans.

The customers under consideration are ('BL03', 'BL05') who have taken the following loans 

LAF01	-	TERM LOAN- NON EMI - FCY
LAF06	-	HOUSING LOAN - GEN PUBLIC - FCY
LAL02	-	TERM LOAN- EMI- LCY
LAL03	-	SHORT TERM LOAN - LCY
LAL06	-	HOUSING LOAN - GEN PUBLIC - LCY
LAL10	-	ASSET FINANCE PUBLIC- EMI - LCY
LAL21	-	HIRE PURCHASE -GROUP COMPANIES - LCY
LAL27	-	WORK PLACE BANKING FACILITY
LAL30	-	STOCK FINANCE LOAN - LCY
LAL32	-	GOVERNMENT SCHEME WORK PLACE BANKING FACILITY

The variables used to build this model are 
'REP_PERD_MTHS', 'no_of_loan_accounts','FLOW_AMT', 'median_eod_bal_3_weeks', 'DIS_AMT','avg_credit_to_debit_amt_ratio_3_weeks', 'median_credit_to_debit_ratio_3_weeks','no_of_non_loan_accounts', 'MEDIAN_WEEKLY_DEBIT_CREDIT_COUNT_RATIO', 'AGE_WITH_BANK'

The attached notebook has both EDA and ModelLing.


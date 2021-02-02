1) login		[Username, password] 
2) logout
3) register 		[use same fields but table should be name as (admin)] 
4) edit profile 	[update the admin table]
5) 'Diabetes' 	- 	[view all records in tabular form (table_csv) 'update' operation can perform]
6) 'Users' 	-	[view all user profiles and edit/delete operation can perform]
7) 'patients Record' 	[view all record how many patients have been saved their data - can see who is diabetic and who is safe]


if not running then use:

Step1: pip3 install -r requirements.txt
step2: python3 Driver.py migrate
step3: streamlit run Driver.py

if any attribute error: use this command; pip3 install --upgrade protobuf
if getting any Nomodule error use this command; pip3 install -U scikit-learn scipy matplotlib


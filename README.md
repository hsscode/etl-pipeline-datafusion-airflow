![image](https://github.com/user-attachments/assets/b975468a-7e68-4b37-a528-55048f79a5a5)




Sol: 

Python > cloud storage > cloud data fusion (no coe solution for data transformation) > big query >  Looker 

This whole flow will be automated by composer-airflow 



Step1: Created code in python for data  extract and uploading it to the bucket 


Note: gcloud auth application-default login 

(this command help to authenticate the device with gcp) 


Step2: then created data fusion pipeline to upload data from the bucket  to the big query table using data fusion instance.

Step3:  to automate these steps used composer. There created 2 jobs and kept in 1 dag.











## 1 - Screenshots of the database creation and configuration process in both Azure and GCP
### **Azure**
### Add resource group, database name, and server
<img width="745" alt="Screenshot 2024-10-18 at 12 59 26" src="https://github.com/user-attachments/assets/60068356-8e5f-41d1-a4b6-a7575ca3bace">

#### Create a new server if needed
<img width="770" alt="Screenshot 2024-10-18 at 12 51 00" src="https://github.com/user-attachments/assets/1c2cbf60-dae5-4a4c-8ae4-1ccb07e87abe">

### Adjust Networking settings to public endpoint
<img width="736" alt="Screenshot 2024-10-18 at 13 01 59" src="https://github.com/user-attachments/assets/b752f4cf-3d13-4ed3-bb0d-bca2be57f6e5">

### Keep Security and Additional settings the default
<img width="721" alt="Screenshot 2024-10-18 at 13 06 57" src="https://github.com/user-attachments/assets/434359a6-4033-45d3-9da8-eac7c3077cbc">
<img width="728" alt="Screenshot 2024-10-18 at 13 06 48" src="https://github.com/user-attachments/assets/9409febb-2a31-4248-b119-c4e1755df177">

### You have created your SQL database!
<img width="1470" alt="Screenshot 2024-10-18 at 13 13 27" src="https://github.com/user-attachments/assets/b33668f1-0700-407e-b5ea-adb3c777f3e1">

### **GCP**
### Choose a Cloud SQL Edition
<img width="516" alt="Screenshot 2024-10-18 at 13 44 23" src="https://github.com/user-attachments/assets/e81e57b7-4aec-4f50-ac43-75241a91730b">

### GCP similarly asks for a database (instance) name, password, and region. GCP has a Sandbox environment while Azure only has Production or Development
<img width="538" alt="Screenshot 2024-10-18 at 13 44 37" src="https://github.com/user-attachments/assets/37753799-4d58-4f8e-9450-dd4fda931ead">

### Other configurations are very similar to what is found in Azure but in a more simple format
<img width="521" alt="Screenshot 2024-10-18 at 13 47 22" src="https://github.com/user-attachments/assets/78830e10-d67a-4235-bde0-4a512e1d79cd">

### Your GCP instance is created!
<img width="1406" alt="Screenshot 2024-10-18 at 13 49 01" src="https://github.com/user-attachments/assets/6bd4e631-40bb-4b6b-b344-72dc88eb3d78">

## 2 - BigQuery dataset creation and query results

## 3 - Documentation of the monitoring process for both Azure MySQL and GCP MySQL/BigQuery
### **Azure**
### By going to the Monitoring tab, you can view different metrics
<img width="273" alt="Screenshot 2024-10-18 at 13 31 00" src="https://github.com/user-attachments/assets/aed61a62-66c6-47ca-bd57-7b0480f08000">
<img width="583" alt="Screenshot 2024-10-18 at 13 23 49" src="https://github.com/user-attachments/assets/d470496d-af6e-4710-b937-33695676435d">
<img width="1163" alt="Screenshot 2024-10-18 at 13 30 28" src="https://github.com/user-attachments/assets/09a23644-fe34-4194-b925-77df4f4b2237">

### Under Intelligent Performance, go to Query Performance Insight to view query duration, execution count, and resource consumption for each query
<img width="1462" alt="Screenshot 2024-10-18 at 13 32 26" src="https://github.com/user-attachments/assets/324618ed-4623-4644-ba82-f784647a3272">

### **GCP**

## 4 - Reflections on the differences between managing databases on Azure and GCP
Managing databases on Azure and GCP presents distinct approaches. Azure emphasizes integration with Microsoft products through services like Azure SQL Database and Cosmos DB, while GCP focuses on scalability and performance, particularly with Cloud SQL and BigQuery. GCP also appeals to developers with its strong Kubernetes support. Ultimately, the choice depends on ecosystem alignment, specific features, and user familiarity.



